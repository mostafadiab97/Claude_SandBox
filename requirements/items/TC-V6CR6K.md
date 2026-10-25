---
id: TC-V6CR6K
type: test-case
title: "Verify: Menu system restores the operating mode"
status: Draft
owner: M. Farouk
tags:
  - cost
  - connectivity
parent: INFO-HTSZ15
order: 40
links:
  - type: verifies
    target: SYS-8PHDX1
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
