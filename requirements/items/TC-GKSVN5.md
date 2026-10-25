---
id: TC-GKSVN5
type: test-case
title: "Verify: Menu system stores error conditions"
status: Approved
priority: High
tags:
  - ux
  - release-2.0
  - i18n
parent: INFO-HTSZ15
order: 1120
links:
  - type: verifies
    target: SYS-J06B7Z
  - type: verifies
    target: SW-6CPXNC
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
