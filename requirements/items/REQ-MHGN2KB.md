---
id: TC-VZH80Q
type: test-case
title: "Verify: Power supply displays error conditions"
status: Approved
priority: Medium
parent: INFO-MACGC3
order: 270
links:
  - type: verifies
    target: SYS-VJF36E
    confirmed: 54c7b8c371d8
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
