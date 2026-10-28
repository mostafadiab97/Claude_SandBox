---
id: REQ-SBYC58K
type: test-case
title: "Verify: Telemetry pipeline synchronises sensor readings"
status: Approved
priority: High
owner: محمد علي
tags:
  - connectivity
  - performance
former-id: TC-6J7W41
parent: REQ-8351896
order: b1O
links:
  - type: verifies
    target: REQ-TF5DFFZ
    confirmed: 11c446c78b24
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
