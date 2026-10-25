---
id: TC-54B1Z4
type: test-case
title: "Verify: Backlight reports humidity values"
status: Approved
priority: High
owner: J. Müller
tags:
  - power
parent: INFO-HTSZ15
order: 1140
links:
  - type: verifies
    target: SYS-1YMXAH
    confirmed: 4e76eb2ccede
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
