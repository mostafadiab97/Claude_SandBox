---
id: TC-A2WYHP
type: test-case
title: "Verify: Bluetooth LE link synchronises the set point"
status: Approved
tags:
  - release-2.0
parent: INFO-F0M7VC
order: 1150
links:
  - type: verifies
    target: SYS-7W8YGY
    confirmed: aca44262add5
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
