---
id: TC-RE95ZQ
type: test-case
title: "Verify: Main PCB calibrates the room temperature"
status: Draft
priority: High
owner: R. Nabil
tags:
  - connectivity
parent: INFO-MACGC3
order: 1570
links:
  - type: verifies
    target: SYS-NYS190
    confirmed: ed22064137e9
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Display schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
