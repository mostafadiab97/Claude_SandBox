---
id: TC-DK7X1N
type: test-case
title: "Regression: Over-temperature monitor synchronises access tokens"
status: Approved
owner: S. Adel
tags:
  - ux
  - release-2.0
  - regulatory
parent: INFO-ECHASH
order: 930
links:
  - type: verifies
    target: SYS-M5YEH7
    confirmed: 82e2e5978f31
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
