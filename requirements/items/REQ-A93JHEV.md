---
id: TC-GV8MFQ
type: test-case
title: Hub verification 15
status: Obsolete
priority: High
owner: L. Samir
parent: INFO-ECHASH
order: 240
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Validate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
