---
id: REQ-C8XHK09
type: test-case
title: Hub verification 18
status: Review
priority: High
tags:
  - cost
former-id: TC-Z4XA99
parent: REQ-6H15AV2
order: aQ
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
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
