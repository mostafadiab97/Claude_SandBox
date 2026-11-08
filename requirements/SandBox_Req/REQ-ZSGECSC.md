---
id: REQ-ZSGECSC
type: test-case
title: Hub verification 32
status: Approved
priority: High
owner: Y. Saber
tags:
  - accessibility
  - connectivity
former-id: TC-GP91AC
parent: REQ-6H15AV2
order: ae
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
