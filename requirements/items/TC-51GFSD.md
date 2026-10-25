---
id: TC-51GFSD
type: test-case
title: "Verify: Boiler interface displays firmware images"
status: Review
priority: High
owner: É. Laurent
parent: INFO-MS9DAG
order: 1350
links:
  - type: verifies
    target: SYS-SJH59J
  - type: verifies
    target: SW-A00Y82
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
