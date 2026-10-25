---
id: TC-8BSNGW
type: test-case
title: Hub verification 27
status: Draft
priority: Low
owner: M. Farouk
tags:
  - connectivity
  - EMC
parent: INFO-ECHASH
order: 360
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
