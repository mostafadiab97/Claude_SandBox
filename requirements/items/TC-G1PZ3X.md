---
id: TC-G1PZ3X
type: test-case
title: "Verify: Telemetry pipeline detects humidity values"
status: Draft
priority: High
tags:
  - connectivity
parent: INFO-7P4D8D
order: 1610
links:
  - type: verifies
    target: SYS-27ZRZ6
    confirmed: 2208a37cfcbe
  - type: verifies
    target: SW-EPA3J6
    confirmed: 2dee49b460da
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
