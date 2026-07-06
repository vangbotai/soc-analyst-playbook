# False Positive Investigation Guide

## Definition

A false positive is a security alert that appears suspicious but is ultimately determined to be legitimate or expected activity.

## Common Causes

* Scheduled system maintenance
* Software updates
* Authorized administrative activity
* Vulnerability scans
* Backup software
* Security tools performing routine tasks

## Validation Checklist

Before closing an alert, verify:

* The user is authorized.
* The device is recognized.
* The activity matches expected business operations.
* No additional suspicious events occurred.
* Available logs support the conclusion.

## Documentation

Record:

* Why the alert was generated.
* Evidence reviewed.
* Reason it was determined to be benign.
* Date and analyst notes.

Proper documentation helps improve future detection accuracy and reduces repeated investigations.

