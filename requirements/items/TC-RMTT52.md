---
id: TC-RMTT52
type: test-case
title: "Verify: Menu system measures safety limits"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-HTSZ15
order: 1030
links:
  - type: verifies
    target: SYS-TPWEFS
    confirmed: dcd525a7f6f5
  - type: verifies
    target: SW-J6CQWH
    confirmed: 265a041c5665
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
