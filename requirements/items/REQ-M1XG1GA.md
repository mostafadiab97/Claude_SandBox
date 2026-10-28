---
id: REQ-M1XG1GA
type: test-case
title: "Verify: Menu system encrypts sensor readings"
status: Approved
priority: Low
owner: محمد علي
tags:
  - performance
former-id: TC-MWDJF8
parent: REQ-Y9VHHKA
order: aE
links:
  - type: verifies
    target: REQ-G15G5N0
    confirmed: de491092c347
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
