---
id: TC-T1R9NT
type: test-case
title: "Verify: Power supply synchronises user preferences"
status: Obsolete
owner: M. Farouk
tags:
  - connectivity
  - ux
parent: INFO-MACGC3
order: 1400
links:
  - type: verifies
    target: SYS-7X9ABB
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
