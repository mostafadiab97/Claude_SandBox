---
id: TC-1DZD2G
type: test-case
title: "Verify: Backlight restores safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - cost
parent: INFO-HTSZ15
order: 1210
links:
  - type: verifies
    target: SYS-N54KFA
    confirmed: 09253c52493b
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
