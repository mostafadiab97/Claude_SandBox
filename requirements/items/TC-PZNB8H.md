---
id: TC-PZNB8H
type: test-case
title: "Verify: Mobile app displays the operating mode"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - release-1.0
parent: INFO-J0FETE
order: 480
links:
  - type: verifies
    target: SYS-QK55NH
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
