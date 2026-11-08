---
id: REQ-W6NJJWD
type: test-case
title: Hub verification 29
status: Approved
priority: High
owner: محمد علي
former-id: TC-TKWW2D
parent: REQ-6H15AV2
order: ab
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
