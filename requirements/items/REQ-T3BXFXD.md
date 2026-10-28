---
id: REQ-T3BXFXD
type: test-case
title: "Verify: Menu system notifys the room temperature"
status: Obsolete
priority: Medium
owner: L. Samir
tags:
  - performance
  - i18n
former-id: TC-T0MT9T
parent: REQ-Y9VHHKA
order: aS
links:
  - type: verifies
    target: REQ-B5QM2ZG
    confirmed: 02e3c6ed2cec
  - type: verifies
    target: REQ-Y6AM28S
    confirmed: 789b723216ac
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
