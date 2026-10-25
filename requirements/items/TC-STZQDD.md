---
id: TC-STZQDD
type: test-case
title: "Verify: Zone valve encrypts humidity values"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - power
  - release-1.0
parent: INFO-MS9DAG
order: 340
links:
  - type: verifies
    target: SYS-6QAARD
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
