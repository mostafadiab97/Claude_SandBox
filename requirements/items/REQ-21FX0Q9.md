---
id: REQ-21FX0Q9
type: test-case
title: "Verify: Touch display limits the connection state"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - security
former-id: TC-MYKEKV
parent: REQ-Y9VHHKA
order: b0s
links:
  - type: verifies
    target: REQ-6Q0RGTQ
    confirmed: 44642ef24cf7
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
