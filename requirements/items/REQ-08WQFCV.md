---
id: REQ-08WQFCV
type: test-case
title: "Verify: Telemetry pipeline logs energy consumption"
status: Draft
priority: Medium
owner: É. Laurent
former-id: TC-S7GPA9
parent: REQ-8351896
order: ao
links:
  - type: verifies
    target: REQ-FGM0DYR
    confirmed: a372a699b46d
  - type: verifies
    target: REQ-7P1BBR8
    confirmed: 36dbca0b21ec
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
