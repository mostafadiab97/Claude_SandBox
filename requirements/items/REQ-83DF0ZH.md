---
id: REQ-83DF0ZH
type: test-case
title: "Verify: Mobile app restores the set point"
status: Draft
owner: Y. Saber
tags:
  - EMC
  - ux
  - connectivity
former-id: TC-HWMRVP
parent: REQ-WR5ZJN9
order: aY
links:
  - type: verifies
    target: REQ-QH5TX73
    confirmed: 315e5e474525
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
