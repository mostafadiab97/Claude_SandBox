---
id: TC-MWNX9R
type: test-case
title: Hub verification 25
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - regulatory
  - i18n
parent: INFO-ECHASH
order: 340
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
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
