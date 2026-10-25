---
id: TC-FVZEGQ
type: test-case
title: "Verify: Menu system displays the room temperature"
status: Obsolete
priority: Medium
owner: S. Adel
parent: INFO-HTSZ15
order: 130
links:
  - type: verifies
    target: SYS-JGZMEV
    confirmed: 06d6346c072b
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
