---
id: TC-Q84Z2S
type: test-case
title: "Regression: Heating controller synchronises the set point"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - cost
parent: INFO-ECHASH
order: 960
links:
  - type: verifies
    target: SYS-HS7YMC
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
