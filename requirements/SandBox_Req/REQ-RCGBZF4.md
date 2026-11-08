---
id: REQ-RCGBZF4
type: test-case
title: "Verify: Power supply switchs the set point"
status: Approved
owner: Y. Saber
former-id: TC-J545NA
parent: REQ-F9Z1FYS
order: b1M
links:
  - type: verifies
    target: REQ-CHSRQQ4
    confirmed: 22f4af60b62c
  - type: verifies
    target: REQ-ABMZPA4
    confirmed: a4c82810347b
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
