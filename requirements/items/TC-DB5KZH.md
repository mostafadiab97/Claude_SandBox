---
id: TC-DB5KZH
type: test-case
title: "Verify: Backlight displays energy consumption"
status: Obsolete
priority: High
owner: L. Samir
parent: INFO-HTSZ15
order: 360
links:
  - type: verifies
    target: SYS-ZR9FA9
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
