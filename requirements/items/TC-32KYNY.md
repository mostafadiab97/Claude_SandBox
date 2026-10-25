---
id: TC-32KYNY
type: test-case
title: Hub verification 4
status: Obsolete
priority: Low
owner: R. Nabil
tags:
  - cost
parent: INFO-ECHASH
order: 130
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
