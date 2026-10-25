---
id: TC-YRZK2Q
type: test-case
title: "Verify: Backlight calibrates safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-2.0
  - EMC
parent: INFO-HTSZ15
order: 520
links:
  - type: verifies
    target: SYS-W9R8ZQ
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
