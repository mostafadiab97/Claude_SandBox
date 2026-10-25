---
id: TC-P5YR6R
type: test-case
title: Hub verification 28
status: Review
priority: Low
tags:
  - ux
  - connectivity
  - i18n
parent: INFO-ECHASH
order: 370
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
