---
id: TC-ZB1J97
type: test-case
title: "Verify: Menu system authenticates safety limits"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-HTSZ15
order: 700
links:
  - type: verifies
    target: SYS-Q7FXSQ
    confirmed: 87ab2e4b1288
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
