---
id: TC-F8VB6T
type: test-case
title: "Verify: Backlight validates schedule entries"
status: Review
priority: High
owner: Y. Saber
parent: INFO-HTSZ15
order: 1380
links:
  - type: verifies
    target: SYS-3Z4RXV
    confirmed: 6ca149f912b8
  - type: verifies
    target: SW-V860W7
    confirmed: 56c1b62a6109
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
