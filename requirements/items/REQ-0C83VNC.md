---
id: REQ-0C83VNC
type: test-case
title: "Verify: Heating controller reports humidity values"
status: Draft
priority: High
owner: K. Tanaka
former-id: TC-BBN8M9
parent: REQ-XGWSK2K
order: b0C
links:
  - type: verifies
    target: REQ-R2V07V4
    confirmed: 3379698ed305
  - type: verifies
    target: REQ-MXN6AV4
    confirmed: 00f068d4e6d7
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
