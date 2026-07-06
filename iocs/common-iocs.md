# Common Indicators of Compromise Reference

## Overview

Indicators of Compromise (IOCs) are artifacts or behaviors that may indicate malicious activity or unauthorized access.

SOC analysts use IOCs alongside security tools such as SIEM platforms, endpoint monitoring solutions, and log analysis tools to investigate potential threats.

---

# 1. Network Indicators

## IP Addresses

An IP address may be suspicious when it is associated with:

* Known malicious infrastructure
* Unexpected geographic locations
* Unusual communication patterns
* Connections outside normal business activity

### Investigation Questions

* Has this IP communicated with other systems?
* Is the destination expected?
* Are multiple users connecting to the same address?
* Is the activity occurring at unusual times?

---

## Domains and URLs

Suspicious domains may include:

* Newly created domains
* Typosquatting domains
* Domains impersonating legitimate organizations
* Links associated with phishing attempts

### Investigation Questions

* Does the domain match the expected organization?
* Does the URL redirect unexpectedly?
* Was the link received through suspicious communication?

---

# 2. File Indicators

## File Hashes

A hash is a unique digital fingerprint used to identify files.

Common hash types:

* MD5
* SHA-1
* SHA-256

Analysts compare hashes against threat intelligence sources to determine whether files are known to be malicious.

---

## Suspicious Files

Analysts may review:

* Unknown executables
* Recently created files
* Files in unusual locations
* Files with unexpected extensions

---

# 3. Process Indicators

Suspicious process activity may include:

* Unknown programs executing
* Programs running from temporary folders
* Unexpected administrative tools
* Unusual parent-child process relationships

Example:

```
Microsoft Word
        |
        ↓
PowerShell
        |
        ↓
Unknown Script
```

This type of process chain may require additional investigation.

---

# 4. Account Indicators

Examples:

* Unexpected administrator accounts
* Login activity from unusual locations
* Multiple failed authentication attempts
* Privilege changes

Analysts should review:

* Who performed the action
* When it occurred
* Whether the activity was authorized

---

# 5. PowerShell Indicators

Suspicious PowerShell activity may include:

* Encoded commands
* Downloading files from unknown locations
* Execution from unusual directories
* Hidden execution methods

PowerShell activity should always be evaluated based on context.

---

# 6. Persistence Indicators

Attackers may attempt to maintain access through:

* Scheduled tasks
* Startup programs
* Registry modifications
* New services
* Unauthorized accounts

---

# Analyst Investigation Workflow

When reviewing an IOC:

1. Identify the indicator.
2. Gather additional context.
3. Search related logs.
4. Determine scope and impact.
5. Document findings.
6. Escalate if necessary.

---

# Key Takeaway

IOCs provide valuable evidence during security investigations, but individual indicators should not be analyzed in isolation. Effective SOC analysts combine multiple sources of information to determine whether activity represents a legitimate event or a potential security incident.

