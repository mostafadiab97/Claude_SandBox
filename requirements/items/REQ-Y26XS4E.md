---
id: TC-SVDKQC
type: test-case
title: "Regression: Over-temperature monitor measures sensor readings"
status: Approved
priority: High
owner: J. Müller
tags:
  - release-2.0
parent: INFO-ECHASH
order: 1580
links:
  - type: verifies
    target: SYS-WNE3D0
    confirmed: c41d4d2660da
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
