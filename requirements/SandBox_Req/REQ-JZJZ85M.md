---
id: REQ-JZJZ85M
type: test-case
title: "Verify: Backlight stores the room temperature"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - customer-request
former-id: TC-M8RZX9
parent: REQ-Y9VHHKA
order: aM
links:
  - type: verifies
    target: REQ-DVVNZG6
    confirmed: cb3485657a51
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
