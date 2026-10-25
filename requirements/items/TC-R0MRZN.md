---
id: TC-R0MRZN
type: test-case
title: "Verify: Telemetry pipeline limits the room temperature"
status: Review
priority: Medium
owner: H. Mostafa
parent: INFO-7P4D8D
order: 1420
links:
  - type: verifies
    target: SYS-ZD3S52
    confirmed: 0af8d7691be2
  - type: verifies
    target: SW-PZFQGD
    confirmed: 691fb7a4cd9f
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
