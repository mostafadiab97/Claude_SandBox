---
id: REQ-RTS071P
type: test-case
title: "Verify: Tamper detection displays user preferences"
status: Draft
priority: Low
owner: Y. Saber
tags:
  - ux
former-id: TC-A9GYZ8
parent: REQ-K6FGAY0
order: b0Q
links:
  - type: verifies
    target: REQ-C5C9ZW1
    confirmed: 3febb67033c8
  - type: verifies
    target: REQ-EPMMJ7J
    confirmed: 899ddd8c2261
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
