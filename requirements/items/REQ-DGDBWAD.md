---
id: TC-B1B2Z5
type: test-case
title: "Verify: Backlight restores humidity values"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - release-2.0
parent: INFO-HTSZ15
order: 490
links:
  - type: verifies
    target: SYS-3J52W8
    confirmed: 92ce5ba8e9a8
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
