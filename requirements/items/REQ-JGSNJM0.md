---
id: REQ-JGSNJM0
type: test-case
title: Hub verification 26
status: Approved
owner: H. Mostafa
tags:
  - release-1.0
former-id: TC-192ENM
parent: REQ-6H15AV2
order: aY
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
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
