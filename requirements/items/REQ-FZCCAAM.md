---
id: TC-K6DYGD
type: test-case
title: "Verify: Telemetry pipeline displays firmware images"
status: Approved
priority: Medium
owner: L. Samir
parent: INFO-7P4D8D
order: 70
links:
  - type: verifies
    target: SYS-175X0G
    confirmed: 3e7e54a5d4f3
  - type: verifies
    target: SW-HQNY5C
    confirmed: ea7ac01e52a8
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
