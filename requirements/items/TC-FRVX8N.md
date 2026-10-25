---
id: TC-FRVX8N
type: test-case
title: Hub verification 33
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - ux
parent: INFO-ECHASH
order: 420
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
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
