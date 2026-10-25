---
id: TC-GKX6G2
type: test-case
title: "Regression: Heating controller measures safety limits"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - connectivity
  - i18n
parent: INFO-ECHASH
order: 1280
links:
  - type: verifies
    target: SYS-DFR9YD
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
