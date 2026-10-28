---
id: TC-49E755
type: test-case
title: "Verify: Telemetry pipeline restores schedule entries"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - safety
  - power
parent: INFO-7P4D8D
order: 1340
links:
  - type: verifies
    target: SYS-X4ZQAJ
    confirmed: 6b28de77da9f
  - type: verifies
    target: SW-73NZH2
    confirmed: 9395fb23e6ef
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
