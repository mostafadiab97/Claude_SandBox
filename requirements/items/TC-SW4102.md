---
id: TC-SW4102
type: test-case
title: Hub verification 19
status: Obsolete
priority: Medium
owner: N. Kamal
tags:
  - regulatory
  - EMC
parent: INFO-ECHASH
order: 280
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
