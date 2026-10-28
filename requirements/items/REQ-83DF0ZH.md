---
id: TC-HWMRVP
type: test-case
title: "Verify: Mobile app restores the set point"
status: Draft
owner: Y. Saber
tags:
  - EMC
  - ux
  - connectivity
parent: INFO-J0FETE
order: 350
links:
  - type: verifies
    target: SYS-GYKHZH
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
