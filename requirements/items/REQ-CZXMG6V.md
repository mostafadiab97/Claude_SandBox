---
id: REQ-CZXMG6V
type: test-case
title: "Regression: Secure boot authenticates energy consumption"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-4VDWF4
parent: REQ-6H15AV2
order: b08
links:
  - type: verifies
    target: REQ-VD3A46J
    confirmed: 96551a11c8e9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
