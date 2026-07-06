# Case Study 03 – Ransomware Detection Alert (Fictional Scenario)

## Scenario

This fictional scenario demonstrates how a SOC analyst might respond to a suspected ransomware event.

## Alert Summary

**Alert Type:** Potential Ransomware Activity

**Severity:** Critical

**Source:** Endpoint Detection and Response (EDR)

## Initial Observation

An endpoint security platform detected unusual file activity, including rapid file modifications and behavior commonly associated with ransomware encryption.

## Investigation Process

A SOC analyst would investigate:

* The affected device
* Logged-in user account
* Recently executed processes
* Modified files
* Network activity
* Additional affected systems

## Indicators of Suspicious Activity

Examples include:

* Large numbers of files modified in a short period
* Unusual file extensions
* Unknown processes accessing many files
* Suspicious scripts or executables
* Communication with unknown external systems

## Response Actions

Potential actions include:

1. Isolate the affected endpoint.
2. Prevent further spread.
3. Collect forensic information.
4. Identify the initial access method.
5. Determine affected systems.
6. Escalate to incident response personnel.

## Recovery Considerations

Recovery may involve:

* Removing malicious software
* Restoring affected systems
* Resetting compromised credentials
* Reviewing security controls
* Documenting lessons learned

## Lessons Learned

Fast detection and proper escalation are critical during ransomware incidents. Analysts must balance rapid containment with evidence preservation to support further investigation.
