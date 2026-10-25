---
id: TC-EA9BER
type: test-case
title: "Verify: Menu system logs user preferences"
status: Obsolete
priority: Medium
parent: INFO-HTSZ15
order: 280
links:
  - type: verifies
    target: SYS-NDHES6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
