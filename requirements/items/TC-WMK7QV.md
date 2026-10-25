---
id: TC-WMK7QV
type: test-case
title: "Verify: Telemetry pipeline validates sensor readings"
status: Approved
tags:
  - cost
parent: INFO-7P4D8D
order: 1380
links:
  - type: verifies
    target: SYS-25VHBZ
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
