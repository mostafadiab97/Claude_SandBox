---
id: REQ-M7KSRJV
type: test-case
title: "Regression: Heat pump driver calibrates the operating mode"
status: Approved
priority: High
owner: S. Adel
tags:
  - power
former-id: TC-J8K4VZ
parent: REQ-6H15AV2
order: b2G
links:
  - type: verifies
    target: REQ-EMA1R60
    confirmed: df19f5a8810f
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
