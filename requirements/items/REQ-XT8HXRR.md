---
id: REQ-XT8HXRR
type: test-case
title: "Regression: Main PCB restores sensor readings"
status: Draft
priority: Low
tags:
  - release-1.0
  - release-2.0
  - safety
former-id: TC-9SNAP0
parent: REQ-6H15AV2
order: b0w
links:
  - type: verifies
    target: REQ-NHG4VB7
    confirmed: 58f0d670cbc1
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
