---
id: REQ-0X8J3JZ
type: test-case
title: Hub verification 17
status: Review
owner: M. Farouk
tags:
  - accessibility
  - release-2.0
former-id: TC-372NKJ
parent: REQ-6H15AV2
order: aP
links:
  - type: verifies
    target: REQ-KK9EHP7
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
