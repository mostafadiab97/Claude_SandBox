---
id: TC-GP91AC
type: test-case
title: Hub verification 32
status: Approved
priority: High
owner: Y. Saber
tags:
  - accessibility
  - connectivity
parent: INFO-ECHASH
order: 410
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
