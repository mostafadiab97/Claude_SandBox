---
id: REQ-Q3PS521
type: test-case
title: Hub verification 16
status: Approved
priority: High
owner: É. Laurent
former-id: TC-7HH1KZ
parent: REQ-6H15AV2
order: aO
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
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
