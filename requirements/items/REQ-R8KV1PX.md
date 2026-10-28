---
id: TC-PJ7QK0
type: test-case
title: "Verify: Schedule editor detects energy consumption"
status: Obsolete
priority: Low
owner: محمد علي
tags:
  - security
  - regulatory
parent: INFO-J0FETE
order: 1160
links:
  - type: verifies
    target: SYS-3JPXMD
    confirmed: 429b4766228a
  - type: verifies
    target: SW-HVF1F0
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
