---
id: TC-MPQ2A2
type: test-case
title: Hub verification 37
status: Approved
owner: A. Hassan
tags:
  - cost
  - security
  - customer-request
parent: INFO-ECHASH
order: 460
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
