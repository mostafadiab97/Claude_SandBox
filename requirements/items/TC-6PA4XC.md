---
id: TC-6PA4XC
type: test-case
title: "Verify: Menu system notifys schedule entries"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - safety
  - release-2.0
  - i18n
parent: INFO-HTSZ15
order: 1070
links:
  - type: verifies
    target: SYS-G8P704
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Report firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
