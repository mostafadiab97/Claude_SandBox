---
id: REQ-13Z0VAD
type: test-case
title: Hub verification 19
status: Obsolete
priority: Medium
owner: N. Kamal
tags:
  - regulatory
  - EMC
former-id: TC-SW4102
parent: REQ-6H15AV2
order: aR
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
