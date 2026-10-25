---
id: TC-77QXRA
type: test-case
title: Hub verification 24
status: Obsolete
priority: High
owner: S. Adel
tags:
  - performance
parent: INFO-ECHASH
order: 330
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
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
