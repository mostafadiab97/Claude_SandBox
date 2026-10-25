---
id: TC-A9GYZ8
type: test-case
title: "Verify: Tamper detection displays user preferences"
status: Draft
priority: Low
owner: Y. Saber
tags:
  - ux
parent: INFO-Z4TW4B
order: 890
links:
  - type: verifies
    target: SYS-4K2HDJ
  - type: verifies
    target: SW-HGBJZZ
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
