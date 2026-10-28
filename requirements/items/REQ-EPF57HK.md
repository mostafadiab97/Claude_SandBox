---
id: TC-SJXXD9
type: test-case
title: "Verify: Tamper detection logs error conditions"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-Z4TW4B
order: 360
links:
  - type: verifies
    target: SYS-49FF9M
    confirmed: de1a22bc8031
  - type: verifies
    target: SW-7NJ840
    confirmed: 598e15ccb9d4
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
