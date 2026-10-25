---
id: TC-DTA7H4
type: test-case
title: "Verify: Menu system measures error conditions"
status: Draft
priority: High
owner: S. Adel
tags:
  - ux
parent: INFO-HTSZ15
order: 300
links:
  - type: verifies
    target: SYS-B8BCQN
    confirmed: 2a3d9dbc24b6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
