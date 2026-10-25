---
id: TC-XTZY2P
type: test-case
title: "Verify: Menu system synchronises schedule entries"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-HTSZ15
order: 1150
links:
  - type: verifies
    target: SYS-8YEDPY
  - type: verifies
    target: SW-2T3SDJ
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
