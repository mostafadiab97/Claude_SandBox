---
id: TC-X79C78
type: test-case
title: "Verify: Status LED calibrates the operating mode"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - cost
parent: INFO-HTSZ15
order: 930
links:
  - type: verifies
    target: SYS-BF1ZYT
    confirmed: a41f5627def3
  - type: verifies
    target: SW-HY8JBJ
    confirmed: e18e4ba5d45b
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
