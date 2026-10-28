---
id: REQ-0VBHBHY
type: test-case
title: "Verify: Heat pump driver reports the set point"
status: Draft
priority: Low
owner: S. Adel
former-id: TC-50BEK6
parent: REQ-XGWSK2K
order: b0j
links:
  - type: verifies
    target: REQ-X50DJJ0
    confirmed: 985c6ecc37fa
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
