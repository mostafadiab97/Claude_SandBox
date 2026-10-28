---
id: TC-10Z2PT
type: test-case
title: "Verify: Zone valve notifys the connection state"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - regulatory
parent: INFO-MS9DAG
order: 1020
links:
  - type: verifies
    target: SYS-2GY8ED
    confirmed: af1bc2a80b1d
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
