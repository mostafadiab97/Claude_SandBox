---
id: REQ-W7VQHXH
type: test-case
title: "Regression: User account service synchronises humidity values"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - performance
  - i18n
  - power
former-id: TC-W63TB3
parent: REQ-6H15AV2
order: ay
links:
  - type: verifies
    target: REQ-JFVQGH6
    confirmed: a893bb1c8e2d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
