---
id: REQ-G0BCSB8
type: test-case
title: "Verify: Tamper detection restores the set point"
status: Approved
priority: Low
owner: S. Adel
tags:
  - performance
former-id: TC-7R0DZA
parent: REQ-K6FGAY0
order: b0X
links:
  - type: verifies
    target: REQ-6ADPEP5
    confirmed: 74f2cdf0b355
  - type: verifies
    target: REQ-61ASS8M
    confirmed: 3b830706ec65
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
