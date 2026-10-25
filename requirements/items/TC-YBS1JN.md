---
id: TC-YBS1JN
type: test-case
title: Hub verification 11
status: Approved
priority: Medium
tags:
  - connectivity
parent: INFO-ECHASH
order: 200
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
