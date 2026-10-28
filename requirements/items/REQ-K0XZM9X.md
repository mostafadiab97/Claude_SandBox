---
id: REQ-K0XZM9X
type: test-case
title: Hub verification 8
status: Review
owner: J. Müller
tags:
  - security
former-id: TC-NR1E9J
parent: REQ-6H15AV2
order: aG
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
