---
id: TC-V2NG4D
type: test-case
title: "Verify: Zone valve measures the connection state"
status: Review
owner: M. Farouk
parent: INFO-MS9DAG
order: 80
links:
  - type: verifies
    target: SYS-0GKFAB
  - type: verifies
    target: SW-MGBSAX
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
