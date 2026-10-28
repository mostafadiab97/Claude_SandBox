---
id: REQ-HFECB4V
type: test-case
title: "Regression: Secure boot measures schedule entries"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - performance
  - EMC
former-id: TC-RYHE43
parent: REQ-6H15AV2
order: ax
links:
  - type: verifies
    target: REQ-5AFTQWT
    confirmed: 7b3dac33b561
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
