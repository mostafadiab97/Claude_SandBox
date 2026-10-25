---
id: TC-A4A8H7
type: test-case
title: "Verify: Menu system displays the connection state"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - performance
  - i18n
  - release-2.0
parent: INFO-HTSZ15
order: 1110
links:
  - type: verifies
    target: SYS-YVNHRY
    confirmed: 586d305ca699
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Log audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
