---
id: REQ-D0DTY92
type: test-case
title: "Verify: Heating controller limits access tokens"
status: Obsolete
priority: Low
owner: L. Samir
tags:
  - safety
  - ux
  - release-1.0
former-id: TC-A02S20
parent: REQ-XGWSK2K
order: b0O
links:
  - type: verifies
    target: REQ-QQZD5VA
    confirmed: 723f7d1c807e
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
