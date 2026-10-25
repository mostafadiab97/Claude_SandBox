---
id: TC-VQGV4X
type: test-case
title: "Verify: Backlight calibrates sensor readings"
status: Draft
priority: Low
owner: S. Adel
parent: INFO-HTSZ15
order: 640
links:
  - type: verifies
    target: SYS-WTN381
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
