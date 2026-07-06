# Case Study 01 – Brute Force Login Attempt (Fictional Scenario)

## Scenario

This fictional scenario demonstrates how a Security Operations Center (SOC) analyst might investigate repeated failed login attempts against a user account.

## Alert Summary

**Alert Type:** Multiple Failed Login Attempts

**Severity:** Medium

**Source:** Authentication Logs

## Initial Observation

A user account generated more than 50 failed login attempts within a five-minute period from a single external IP address.

## Investigation Process

The following questions would guide the investigation:

* Is the affected user a valid employee?
* Has the user recently changed their password?
* Are the login attempts coming from an expected geographic location?
* Were any login attempts eventually successful?
* Have similar alerts been observed from the same IP address?

## Possible Indicators

* Password spraying
* Brute-force attack
* Compromised credentials
* User entering an incorrect password repeatedly

## Recommended Actions

* Review authentication logs.
* Check account lockout events.
* Verify with the user whether the activity was expected.
* Reset the password if compromise is suspected.
* Block the source IP if appropriate.
* Escalate if evidence suggests unauthorized access.

## Lessons Learned

High volumes of failed authentication attempts should always be investigated to determine whether they represent normal user behavior or malicious activity. Proper documentation and evidence collection support accurate incident response.

