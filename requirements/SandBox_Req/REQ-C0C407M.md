---
id: REQ-C0C407M
type: test-case
title: "Verify: Heat pump driver reports safety limits"
status: Approved
priority: High
owner: L. Samir
tags:
  - accessibility
  - release-1.0
  - release-2.0
former-id: TC-TBSYGK
parent: REQ-XGWSK2K
order: b0F
links:
  - type: verifies
    target: REQ-QRWZEWA
    confirmed: 2659248bd16e
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Calibrate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
