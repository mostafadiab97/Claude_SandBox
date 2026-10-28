---
id: TC-Q414JF
type: test-case
title: "Verify: Menu system stores audit records"
status: Approved
priority: High
owner: J. Müller
tags:
  - performance
parent: INFO-HTSZ15
order: 70
links:
  - type: verifies
    target: SYS-F28JAH
    confirmed: d2f3c3322d09
  - type: verifies
    target: SW-BPPPDX
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
