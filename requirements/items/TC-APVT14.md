---
id: TC-APVT14
type: test-case
title: "Regression: Wi-Fi module switchs schedule entries"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - power
  - cost
parent: INFO-ECHASH
order: 950
links:
  - type: verifies
    target: SYS-5NPG22
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
