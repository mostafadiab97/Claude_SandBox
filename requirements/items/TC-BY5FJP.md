---
id: TC-BY5FJP
type: test-case
title: "Verify: Zone valve reports energy consumption"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - connectivity
  - security
  - customer-request
parent: INFO-MS9DAG
order: 570
links:
  - type: verifies
    target: SYS-N8A6YS
  - type: verifies
    target: SW-TGE2C7
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
