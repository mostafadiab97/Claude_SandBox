---
id: TC-372NKJ
type: test-case
title: Hub verification 17
status: Review
owner: M. Farouk
tags:
  - accessibility
  - release-2.0
parent: INFO-ECHASH
order: 260
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
