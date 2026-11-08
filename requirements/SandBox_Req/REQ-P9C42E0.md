---
id: REQ-P9C42E0
type: test-case
title: Hub verification 31
status: Obsolete
priority: Low
owner: Y. Saber
former-id: TC-BGCGHB
parent: REQ-6H15AV2
order: ad
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
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
