# Alert Triage Guide

## Objective

Alert triage is the process of reviewing security alerts to determine whether they represent legitimate security incidents or expected system activity.

## Triage Process

### 1. Review the Alert

Identify:

* Alert type
* Timestamp
* Source device
* Username
* IP address
* Severity level

### 2. Gather Context

Determine:

* Is this activity expected?
* Has this user generated similar alerts previously?
* Is the affected device known?
* Were multiple alerts generated during the same time period?

### 3. Analyze Evidence

Review available logs for:

* Login attempts
* Process execution
* File activity
* Network connections
* Account changes

### 4. Determine Severity

Classify the alert based on:

* Potential business impact
* Likelihood of compromise
* Number of affected systems
* Sensitivity of affected assets

### 5. Decide Next Steps

Possible outcomes include:

* Close as a false positive
* Continue monitoring
* Escalate for further investigation
* Initiate the incident response process

## Best Practices

* Verify facts before making conclusions.
* Document all findings.
* Preserve evidence whenever possible.
* Escalate suspicious activity promptly.
* Follow established organizational procedures.

