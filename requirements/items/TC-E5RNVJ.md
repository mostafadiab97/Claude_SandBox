---
id: TC-E5RNVJ
type: test-case
title: "Verify: Backlight restores the operating mode"
status: Approved
owner: K. Tanaka
tags:
  - safety
  - ux
parent: INFO-HTSZ15
order: 80
links:
  - type: verifies
    target: SYS-8FP865
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
