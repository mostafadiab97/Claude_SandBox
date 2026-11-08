---
id: REQ-AKXJ0GJ
type: test-case
title: "Verify: Touch display displays the connection state"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - ux
former-id: TC-NGBPBK
parent: REQ-Y9VHHKA
order: b0O
links:
  - type: verifies
    target: REQ-DPPPJSC
    confirmed: 5a70ac433dd3
  - type: verifies
    target: REQ-HHZT3QX
    confirmed: f7fe8182d612
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
