---
id: TC-FYM8T3
type: test-case
title: "Verify: Over-temperature monitor synchronises sensor readings"
status: Review
priority: Medium
tags:
  - regulatory
  - ux
parent: INFO-Z4TW4B
order: 540
links:
  - type: verifies
    target: SYS-M0XMTJ
  - type: verifies
    target: SW-6X60Y9
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
