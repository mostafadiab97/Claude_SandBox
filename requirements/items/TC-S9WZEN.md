---
id: TC-S9WZEN
type: test-case
title: "Verify: Zone valve logs the set point"
status: Approved
priority: High
owner: N. Kamal
tags:
  - safety
parent: INFO-MS9DAG
order: 770
links:
  - type: verifies
    target: SYS-QNW27Q
    confirmed: cd250a20af9f
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
