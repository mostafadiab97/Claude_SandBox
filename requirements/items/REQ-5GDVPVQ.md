---
id: REQ-5GDVPVQ
type: test-case
title: "Verify: Menu system stores sensor readings"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - i18n
  - connectivity
former-id: TC-2EB3HQ
parent: REQ-Y9VHHKA
order: b1L
links:
  - type: verifies
    target: REQ-9V4ZDEE
    confirmed: "123689018215"
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
