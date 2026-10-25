---
id: TC-7EDPV6
type: test-case
title: "Verify: Zone valve synchronises relay events"
status: Review
owner: L. Samir
parent: INFO-MS9DAG
order: 1010
links:
  - type: verifies
    target: SYS-4DP5C1
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
