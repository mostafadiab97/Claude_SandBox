---
id: REQ-2TWTC9M
type: test-case
title: Hub verification 39
status: Approved
priority: High
owner: H. Mostafa
former-id: TC-W4FSE0
parent: REQ-6H15AV2
order: al
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Switch relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
