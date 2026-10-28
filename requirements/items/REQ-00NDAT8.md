---
id: TC-5P5CEG
type: test-case
title: "Verify: Telemetry pipeline stores the operating mode"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - performance
parent: INFO-7P4D8D
order: 1410
links:
  - type: verifies
    target: SYS-6YK5CA
    confirmed: 2507133e13d3
  - type: verifies
    target: SW-DTX806
    confirmed: 9183eb0e79f7
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
