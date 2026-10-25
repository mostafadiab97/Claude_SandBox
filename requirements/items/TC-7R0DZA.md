---
id: TC-7R0DZA
type: test-case
title: "Verify: Tamper detection restores the set point"
status: Approved
priority: Low
owner: S. Adel
tags:
  - performance
parent: INFO-Z4TW4B
order: 960
links:
  - type: verifies
    target: SYS-ZVPM29
  - type: verifies
    target: SW-ZJ6HPB
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Validate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
