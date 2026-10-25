---
id: TC-CEQNXN
type: test-case
title: "Verify: Zone valve detects energy consumption"
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-MS9DAG
order: 900
links:
  - type: verifies
    target: SYS-J8Q01T
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
