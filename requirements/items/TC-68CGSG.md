---
id: TC-68CGSG
type: test-case
title: "Verify: Menu system displays user preferences"
status: Approved
owner: Y. Saber
tags:
  - release-2.0
  - regulatory
parent: INFO-HTSZ15
order: 1050
links:
  - type: verifies
    target: SYS-H265S4
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
