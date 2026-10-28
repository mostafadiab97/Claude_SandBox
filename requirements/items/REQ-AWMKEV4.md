---
id: TC-HGS62V
type: test-case
title: "Verify: Zone valve calibrates sensor readings"
status: Approved
priority: High
owner: R. Nabil
tags:
  - cost
  - release-2.0
parent: INFO-MS9DAG
order: 1560
links:
  - type: verifies
    target: SYS-6VZFH1
    confirmed: 2c2479704519
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
