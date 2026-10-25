---
id: TC-J545NA
type: test-case
title: "Verify: Power supply switchs the set point"
status: Approved
owner: Y. Saber
parent: INFO-MACGC3
order: 1470
links:
  - type: verifies
    target: SYS-R6BCVX
  - type: verifies
    target: SW-E3BXE1
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Authenticate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
