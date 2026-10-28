---
id: REQ-JK22D48
type: test-case
title: "Verify: Menu system stores error conditions"
status: Approved
priority: High
tags:
  - ux
  - release-2.0
  - i18n
former-id: TC-GKSVN5
parent: REQ-Y9VHHKA
order: b0n
links:
  - type: verifies
    target: REQ-J32MDNX
    confirmed: 2ddf44dea71d
  - type: verifies
    target: REQ-8YNB1N1
    confirmed: bf52e8c5fcc5
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
