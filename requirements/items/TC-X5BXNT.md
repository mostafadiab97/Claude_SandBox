---
id: TC-X5BXNT
type: test-case
title: "Regression: Relay board encrypts the set point"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - security
  - ux
  - safety
parent: INFO-ECHASH
order: 1050
links:
  - type: verifies
    target: SYS-J3QEM9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
