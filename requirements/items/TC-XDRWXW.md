---
id: TC-XDRWXW
type: test-case
title: "Regression: Power supply displays safety limits"
status: Draft
priority: High
owner: H. Mostafa
parent: INFO-ECHASH
order: 1610
links:
  - type: verifies
    target: SYS-9J0YHF
    confirmed: 3602ee9aa103
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
