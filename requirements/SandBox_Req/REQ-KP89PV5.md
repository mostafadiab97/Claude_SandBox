---
id: REQ-KP89PV5
type: test-case
title: Hub verification 27
status: Draft
priority: Low
owner: M. Farouk
tags:
  - connectivity
  - EMC
former-id: TC-8BSNGW
parent: REQ-6H15AV2
order: aZ
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
