---
id: TC-192ENM
type: test-case
title: Hub verification 26
status: Approved
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-ECHASH
order: 350
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
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
