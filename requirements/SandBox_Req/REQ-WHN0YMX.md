---
id: REQ-WHN0YMX
type: test-case
title: "Verify: Rotary knob authenticates audit records"
status: Approved
priority: Medium
tags:
  - connectivity
  - customer-request
former-id: TC-8X30VJ
parent: REQ-Y9VHHKA
order: aG
links:
  - type: verifies
    target: REQ-BT8KFYN
    confirmed: be94f152bddf
  - type: verifies
    target: REQ-WANX09S
    confirmed: 3d406af483d9
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
