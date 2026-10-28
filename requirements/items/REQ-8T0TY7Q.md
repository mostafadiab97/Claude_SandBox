---
id: TC-76MZHY
type: test-case
title: "Verify: Backlight switchs schedule entries"
status: Obsolete
priority: High
owner: M. Farouk
tags:
  - customer-request
parent: INFO-HTSZ15
order: 180
links:
  - type: verifies
    target: SYS-HN5S5X
    confirmed: 98a2a16336ac
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
