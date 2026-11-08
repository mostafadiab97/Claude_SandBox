---
id: REQ-HDFZSGS
type: test-case
title: Hub verification 11
status: Approved
priority: Medium
tags:
  - connectivity
former-id: TC-YBS1JN
parent: REQ-6H15AV2
order: aJ
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
