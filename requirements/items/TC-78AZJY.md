---
id: TC-78AZJY
type: test-case
title: "Verify: Menu system logs the connection state"
status: Approved
owner: É. Laurent
tags:
  - EMC
  - ux
parent: INFO-HTSZ15
order: 660
links:
  - type: verifies
    target: SYS-ATYYP2
  - type: verifies
    target: SW-ZMFY7T
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
