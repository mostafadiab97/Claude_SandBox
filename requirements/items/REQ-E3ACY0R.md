---
id: REQ-E3ACY0R
type: test-case
title: Hub verification 28
status: Review
priority: Low
tags:
  - ux
  - connectivity
  - i18n
former-id: TC-P5YR6R
parent: REQ-6H15AV2
order: aa
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
