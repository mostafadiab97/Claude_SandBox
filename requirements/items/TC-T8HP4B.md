---
id: TC-T8HP4B
type: test-case
title: Hub verification 1
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-ECHASH
order: 100
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
