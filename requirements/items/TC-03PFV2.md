---
id: TC-03PFV2
type: test-case
title: "Verify: Heating controller notifys audit records"
status: Draft
priority: High
owner: محمد علي
tags:
  - performance
  - connectivity
parent: INFO-MS9DAG
order: 590
links:
  - type: verifies
    target: SYS-3BJR5R
  - type: verifies
    target: SW-3PKYJH
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Limit the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
