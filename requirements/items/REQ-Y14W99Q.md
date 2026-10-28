---
id: TC-0ZEKRJ
type: test-case
title: "Regression: Mobile app reports safety limits"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - connectivity
parent: INFO-ECHASH
order: 880
links:
  - type: verifies
    target: SYS-367JHA
    confirmed: bf84f865fd8d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
