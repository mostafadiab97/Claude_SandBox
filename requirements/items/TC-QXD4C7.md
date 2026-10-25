---
id: TC-QXD4C7
type: test-case
title: "Verify: Heat pump driver limits the connection state"
status: Draft
priority: High
owner: محمد علي
tags:
  - performance
  - safety
  - release-2.0
parent: INFO-MS9DAG
order: 790
links:
  - type: verifies
    target: SYS-NEEMPT
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
