---
id: REQ-BPH9EEW
type: test-case
title: "Verify: Telemetry pipeline displays sensor readings"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - performance
former-id: TC-7TQASG
parent: REQ-8351896
order: aW
links:
  - type: verifies
    target: REQ-9CB5575
    confirmed: 75b98d046d10
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
