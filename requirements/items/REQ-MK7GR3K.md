---
id: REQ-MK7GR3K
type: test-case
title: "Verify: Heat pump driver synchronises the set point"
status: Obsolete
priority: Low
tags:
  - ux
  - release-2.0
former-id: TC-43QT51
parent: REQ-XGWSK2K
order: aZ
links:
  - type: verifies
    target: REQ-RJT2C4K
    confirmed: 046899ea1e41
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
