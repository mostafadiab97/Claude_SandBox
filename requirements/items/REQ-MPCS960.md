---
id: REQ-MPCS960
type: test-case
title: Hub verification 12
status: Approved
priority: High
former-id: TC-VKTX8H
parent: REQ-6H15AV2
order: aK
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
