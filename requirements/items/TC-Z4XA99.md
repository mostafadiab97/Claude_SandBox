---
id: TC-Z4XA99
type: test-case
title: Hub verification 18
status: Review
priority: High
tags:
  - cost
parent: INFO-ECHASH
order: 270
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
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
