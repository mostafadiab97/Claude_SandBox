---
id: REQ-GYK5RG2
type: test-case
title: "Verify: Enclosure validates the connection state"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - i18n
  - ux
former-id: TC-T49147
parent: REQ-F9Z1FYS
order: b07
links:
  - type: verifies
    target: REQ-1Y42YEX
    confirmed: 6024967bb648
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
