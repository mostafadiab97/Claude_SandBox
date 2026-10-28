---
id: TC-85NJEW
type: test-case
title: "Regression: Menu system reports firmware images"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - regulatory
parent: INFO-ECHASH
order: 1950
links:
  - type: verifies
    target: SYS-34B7MH
    confirmed: 9aafb86ae7fb
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
