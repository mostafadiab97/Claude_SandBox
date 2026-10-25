---
id: TC-BWTS02
type: test-case
title: "Verify: Heat pump driver displays the connection state"
status: Approved
priority: High
owner: S. Adel
tags:
  - release-1.0
  - cost
parent: INFO-MS9DAG
order: 1460
links:
  - type: verifies
    target: SYS-D1ZDY9
  - type: verifies
    target: SW-YH3CS4
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
