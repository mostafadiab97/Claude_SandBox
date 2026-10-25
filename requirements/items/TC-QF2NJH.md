---
id: TC-QF2NJH
type: test-case
title: "Regression: Tamper detection notifys the set point"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - EMC
  - cost
parent: INFO-ECHASH
order: 1540
links:
  - type: verifies
    target: SYS-MR5CRK
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
