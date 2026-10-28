---
id: REQ-S0YWERZ
type: test-case
title: "Verify: Touch display validates schedule entries"
status: Approved
priority: Low
owner: محمد علي
tags:
  - ux
  - regulatory
former-id: TC-8WDBR2
parent: REQ-Y9VHHKA
order: b1M
links:
  - type: verifies
    target: REQ-5TTMZGQ
    confirmed: 7483f5483c58
  - type: verifies
    target: REQ-MQK9CB8
    confirmed: 74dc91e27dbd
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
