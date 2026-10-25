---
id: TC-9BVKQ5
type: test-case
title: Hub verification 40
status: Approved
priority: Low
owner: Y. Saber
tags:
  - accessibility
  - EMC
parent: INFO-ECHASH
order: 490
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
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
