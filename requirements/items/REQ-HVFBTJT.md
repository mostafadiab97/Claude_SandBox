---
id: TC-A2RJJX
type: test-case
title: "Verify: Telemetry pipeline detects the set point"
status: Review
priority: Medium
owner: L. Samir
tags:
  - EMC
  - power
parent: INFO-7P4D8D
order: 500
links:
  - type: verifies
    target: SYS-3ZGG1G
    confirmed: 805d152578fb
  - type: verifies
    target: SW-7KW60G
    confirmed: 7a9b0fc62add
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
