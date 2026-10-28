---
id: TC-YZVPTY
type: test-case
title: "Verify: Power supply stores the operating mode"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - safety
parent: INFO-MACGC3
order: 710
links:
  - type: verifies
    target: SYS-C9BFKW
    confirmed: 0dcc5954ae38
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
