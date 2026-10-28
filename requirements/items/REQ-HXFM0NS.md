---
id: REQ-HXFM0NS
type: test-case
title: "Verify: Regulation loop encrypts the room temperature"
status: Approved
priority: Low
owner: A. Hassan
former-id: TC-23EW3J
parent: REQ-XGWSK2K
order: b11
links:
  - type: verifies
    target: REQ-QG4NKYK
    confirmed: 13efe84ae7ac
  - type: verifies
    target: REQ-QEHRESA
    confirmed: dec77b70daa1
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
