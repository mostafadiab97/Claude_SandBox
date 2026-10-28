---
id: TC-BB7MEZ
type: test-case
title: Hub verification 14
status: Review
priority: Low
owner: Y. Saber
tags:
  - security
  - i18n
  - safety
parent: INFO-ECHASH
order: 230
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
