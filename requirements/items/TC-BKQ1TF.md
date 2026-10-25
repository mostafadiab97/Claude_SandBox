---
id: TC-BKQ1TF
type: test-case
title: "Verify: Main PCB stores sensor readings"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - connectivity
parent: INFO-MACGC3
order: 1000
links:
  - type: verifies
    target: SYS-JHK0D7
    confirmed: a8c42ffc28bc
  - type: verifies
    target: SW-XM6CSF
    confirmed: a824afd3c2ab
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
