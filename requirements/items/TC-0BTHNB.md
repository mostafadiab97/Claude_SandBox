---
id: TC-0BTHNB
type: test-case
title: "Verify: Backlight synchronises safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - accessibility
  - performance
parent: INFO-HTSZ15
order: 390
links:
  - type: verifies
    target: SYS-H3FFZV
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
