---
id: TC-5SD6D7
type: test-case
title: "Verify: Main PCB displays sensor readings"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - ux
  - safety
parent: INFO-MACGC3
order: 40
links:
  - type: verifies
    target: SYS-80ZJ33
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
