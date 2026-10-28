---
id: REQ-R8KV1PX
type: test-case
title: "Verify: Schedule editor detects energy consumption"
status: Obsolete
priority: Low
owner: محمد علي
tags:
  - security
  - regulatory
former-id: TC-PJ7QK0
parent: REQ-WR5ZJN9
order: b0r
links:
  - type: verifies
    target: REQ-8WVK5KN
    confirmed: 429b4766228a
  - type: verifies
    target: REQ-K6QWAC0
    confirmed: 7564939a0f77
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
