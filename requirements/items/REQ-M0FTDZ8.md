---
id: REQ-M0FTDZ8
type: test-case
title: "Verify: Mobile app displays the operating mode"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - release-1.0
former-id: TC-PZNB8H
parent: REQ-WR5ZJN9
order: al
links:
  - type: verifies
    target: REQ-E79YMDC
    confirmed: 3934c54c3f62
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
