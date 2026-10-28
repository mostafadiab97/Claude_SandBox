---
id: TC-6KR06F
type: test-case
title: "Verify: Tamper detection synchronises firmware images"
status: Approved
priority: Low
tags:
  - safety
parent: INFO-Z4TW4B
order: 1310
links:
  - type: verifies
    target: SYS-B92MZT
    confirmed: 4ea3d699c52a
  - type: verifies
    target: SW-GD1AD4
    confirmed: 5d785516a115
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
