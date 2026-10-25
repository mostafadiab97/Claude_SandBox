---
id: TC-SF6N2K
type: test-case
title: "Verify: Telemetry pipeline authenticates energy consumption"
status: Approved
owner: A. Hassan
tags:
  - safety
  - connectivity
parent: INFO-7P4D8D
order: 1660
links:
  - type: verifies
    target: SYS-TX0P0A
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
