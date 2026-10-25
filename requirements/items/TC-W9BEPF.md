---
id: TC-W9BEPF
type: test-case
title: "Verify: Menu system restores humidity values"
status: Obsolete
priority: High
tags:
  - release-2.0
  - regulatory
parent: INFO-HTSZ15
order: 750
links:
  - type: verifies
    target: SYS-19AJTE
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
