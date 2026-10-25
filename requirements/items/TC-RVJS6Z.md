---
id: TC-RVJS6Z
type: test-case
title: "Verify: Main PCB validates the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - cost
parent: INFO-MACGC3
order: 1100
links:
  - type: verifies
    target: SYS-DKB6WA
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Calibrate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
