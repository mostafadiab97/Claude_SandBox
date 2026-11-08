---
id: REQ-MRPFN0F
type: test-case
title: Hub verification 9
status: Review
priority: High
owner: K. Tanaka
tags:
  - release-1.0
  - ux
former-id: TC-2C47ME
parent: REQ-6H15AV2
order: aH
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
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
