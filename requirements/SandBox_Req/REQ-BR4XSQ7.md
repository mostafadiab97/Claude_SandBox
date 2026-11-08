---
id: REQ-BR4XSQ7
type: test-case
title: "Verify: Power supply detects the room temperature"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - power
former-id: TC-RQQE5C
parent: REQ-F9Z1FYS
order: b1b
links:
  - type: verifies
    target: REQ-GTNV20Q
    confirmed: a25afcb373b1
  - type: verifies
    target: REQ-SRRDXSE
    confirmed: 58b332ca4f54
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
