---
id: TC-0WHVXH
type: test-case
title: "Verify: Heating controller synchronises the set point"
status: Approved
owner: É. Laurent
tags:
  - EMC
parent: INFO-MS9DAG
order: 260
links:
  - type: verifies
    target: SYS-HS7YMC
  - type: verifies
    target: SW-XMXYED
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
