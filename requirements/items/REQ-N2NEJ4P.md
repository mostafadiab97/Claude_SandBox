---
id: REQ-N2NEJ4P
type: test-case
title: Hub verification 10
status: Review
priority: High
owner: S. Adel
former-id: TC-F5JJ4S
parent: REQ-6H15AV2
order: aI
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
