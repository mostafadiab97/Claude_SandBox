---
id: REQ-ZJK60JM
type: test-case
title: "Verify: Menu system stores audit records"
status: Approved
priority: High
owner: J. Müller
tags:
  - performance
former-id: TC-Q414JF
parent: REQ-Y9VHHKA
order: a6
links:
  - type: verifies
    target: REQ-XY2H6BS
    confirmed: d2f3c3322d09
  - type: verifies
    target: REQ-6865VC7
    confirmed: 7619d6624a37
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Calibrate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
