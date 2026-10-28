---
id: TC-6DBPWZ
type: test-case
title: "Regression: Regulation loop encrypts the set point"
status: Approved
priority: High
owner: H. Mostafa
parent: INFO-ECHASH
order: 1990
links:
  - type: verifies
    target: SYS-5M0EN6
    confirmed: 6b2f33a2ace5
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
