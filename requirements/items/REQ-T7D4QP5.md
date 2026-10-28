---
id: REQ-T7D4QP5
type: test-case
title: "Regression: Boiler interface stores audit records"
status: Draft
priority: Medium
owner: R. Nabil
former-id: TC-0QDDPS
parent: REQ-6H15AV2
order: b04
links:
  - type: verifies
    target: REQ-T1AHZJK
    confirmed: 06bc752da75c
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
