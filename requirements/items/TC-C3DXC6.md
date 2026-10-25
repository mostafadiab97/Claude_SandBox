---
id: TC-C3DXC6
type: test-case
title: "Verify: Telemetry pipeline stores energy consumption"
status: Review
priority: High
owner: L. Samir
parent: INFO-7P4D8D
order: 1240
links:
  - type: verifies
    target: SYS-D7FGDK
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
