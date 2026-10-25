---
id: TC-A1BB7R
type: test-case
title: "Verify: Main PCB switchs humidity values"
status: Approved
owner: محمد علي
tags:
  - power
parent: INFO-MACGC3
order: 120
links:
  - type: verifies
    target: SYS-2094E7
    confirmed: a4e7c0d76393
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
