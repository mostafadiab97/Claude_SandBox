---
id: TC-7THS3R
type: test-case
title: "Verify: Backlight synchronises user preferences"
status: Approved
priority: High
owner: M. Farouk
tags:
  - ux
  - security
parent: INFO-HTSZ15
order: 1370
links:
  - type: verifies
    target: SYS-7Q4FYP
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
