---
id: TC-TYHZZ5
type: test-case
title: "Verify: Menu system measures humidity values"
status: Obsolete
priority: High
owner: H. Mostafa
parent: INFO-HTSZ15
order: 790
links:
  - type: verifies
    target: SYS-8ZNJBE
    confirmed: d6a67816b8b6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
