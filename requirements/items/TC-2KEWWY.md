---
id: TC-2KEWWY
type: test-case
title: "Verify: Enclosure switchs audit records"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - connectivity
parent: INFO-MACGC3
order: 1270
links:
  - type: verifies
    target: SYS-E3W0C4
    confirmed: 6069f1d540ab
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
