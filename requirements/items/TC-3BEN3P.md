---
id: TC-3BEN3P
type: test-case
title: "Verify: Zone valve encrypts safety limits"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
  - EMC
parent: INFO-MS9DAG
order: 230
links:
  - type: verifies
    target: SYS-849P26
    confirmed: 4fcdac202dc1
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
