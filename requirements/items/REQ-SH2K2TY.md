---
id: REQ-SH2K2TY
type: test-case
title: "Verify: Battery backup detects safety limits"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-8EQ56V
parent: REQ-F9Z1FYS
order: b0y
links:
  - type: verifies
    target: REQ-R9KTZAB
    confirmed: 71372d39e051
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
