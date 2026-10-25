---
id: TC-T0MT9T
type: test-case
title: "Verify: Menu system notifys the room temperature"
status: Obsolete
priority: Medium
owner: L. Samir
tags:
  - performance
  - i18n
parent: INFO-HTSZ15
order: 290
links:
  - type: verifies
    target: SYS-S17F3W
  - type: verifies
    target: SW-8S81RT
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
