---
id: TC-AFD83Z
type: test-case
title: "Verify: Backlight encrypts sensor readings"
status: Approved
priority: Medium
tags:
  - power
parent: INFO-HTSZ15
order: 340
links:
  - type: verifies
    target: SYS-V6YEW7
  - type: verifies
    target: SW-R4W44X
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
