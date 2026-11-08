---
id: REQ-SD5ZA8M
type: test-case
title: "Verify: Backlight synchronises user preferences"
status: Approved
priority: High
owner: M. Farouk
tags:
  - ux
  - security
former-id: TC-7THS3R
parent: REQ-Y9VHHKA
order: b1C
links:
  - type: verifies
    target: REQ-RBJSQM3
    confirmed: af798c8aaa0c
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
