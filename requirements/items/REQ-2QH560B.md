---
id: TC-5M4AV7
type: test-case
title: "Verify: Main PCB restores humidity values"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - safety
  - release-2.0
  - connectivity
parent: INFO-MACGC3
order: 870
links:
  - type: verifies
    target: SYS-2SXPK4
    confirmed: a35d491379ed
  - type: verifies
    target: SW-54RD93
    confirmed: 8da42f132cf2
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
