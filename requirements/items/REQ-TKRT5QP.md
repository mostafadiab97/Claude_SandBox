---
id: TC-RYCZFZ
type: test-case
title: "Verify: Main PCB stores sensor readings"
status: Approved
owner: É. Laurent
tags:
  - security
  - safety
  - release-1.0
parent: INFO-MACGC3
order: 880
links:
  - type: verifies
    target: SYS-5C94DF
    confirmed: c00f25df31a0
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
