---
id: TC-S7GPA9
type: test-case
title: "Verify: Telemetry pipeline logs energy consumption"
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-7P4D8D
order: 510
links:
  - type: verifies
    target: SYS-HV5YB5
    confirmed: a372a699b46d
  - type: verifies
    target: SW-GP4XWS
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
