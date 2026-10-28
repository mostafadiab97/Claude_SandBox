---
id: REQ-Q7WGKD0
type: test-case
title: "Verify: Regulation loop notifys the room temperature"
status: Draft
priority: High
owner: L. Samir
tags:
  - security
former-id: TC-7MEGMB
parent: REQ-XGWSK2K
order: b1O
links:
  - type: verifies
    target: REQ-WWGXTCZ
    confirmed: 076f90a0ea7e
  - type: verifies
    target: REQ-DXDFRXW
    confirmed: 4c4f1f47baa6
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
