---
id: TC-S911FW
type: test-case
title: Hub verification 2
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - safety
  - connectivity
parent: INFO-ECHASH
order: 110
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
