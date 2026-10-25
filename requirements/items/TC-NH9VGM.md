---
id: TC-NH9VGM
type: test-case
title: "Verify: Backlight restores access tokens"
status: Draft
priority: Medium
parent: INFO-HTSZ15
order: 610
links:
  - type: verifies
    target: SYS-44HBM9
  - type: verifies
    target: SW-J9HHJH
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
