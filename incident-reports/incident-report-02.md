# Incident Report 02 – Suspicious PowerShell Execution

## Incident Overview

**Incident Name:** Suspicious PowerShell Activity Detected

**Severity:** High

**Status:** Investigation Completed

---

## Executive Summary

A security alert was generated after detecting suspicious PowerShell activity on an endpoint. The activity required investigation to determine whether the execution was part of normal administrative activity or potentially malicious behavior.

---

## Detection Source

The event was identified through endpoint monitoring and security alerting.

Potential detection sources include:

* Endpoint Detection and Response (EDR)
* Security Information and Event Management (SIEM)
* Windows event logging

---

## Affected Assets

Potentially affected:

* User workstation
* User account
* PowerShell execution environment

---

## Timeline

| Time  | Event                                    |
| ----- | ---------------------------------------- |
| 14:00 | Suspicious PowerShell execution detected |
| 14:05 | Security alert generated                 |
| 14:15 | User and endpoint information reviewed   |
| 14:45 | Investigation completed                  |

---

## Investigation Findings

The investigation focused on:

* PowerShell command activity
* User account associated with execution
* Parent process responsible for launching PowerShell
* Network connections created during execution
* Additional files or processes created

PowerShell is a legitimate Windows administration tool but can also be abused by attackers to execute commands, download malicious files, or avoid detection.

---

## Indicators of Concern

Potential indicators included:

* Encoded PowerShell commands
* Unexpected PowerShell execution
* Commands launched from unusual locations
* Suspicious outbound network connections
* Execution by an unexpected user account

---

## Impact Assessment

No confirmed compromise was identified within this fictional scenario.

However, suspicious PowerShell activity can indicate:

* Malware execution
* Unauthorized administrative activity
* Attempts to establish persistence
* Credential theft activity

---

## Response Actions

Recommended response actions:

1. Review PowerShell logs and related security events.
2. Verify whether the activity was authorized.
3. Investigate related processes and network activity.
4. Search for similar activity across other systems.
5. Escalate if evidence suggests malicious behavior.

---

## Lessons Learned

PowerShell activity should be evaluated based on context rather than automatically considered malicious. Analysts must consider the user, system, command details, and surrounding events before determining whether escalation is necessary.

