---
id: TC-FW3SHK
type: test-case
title: "Verify: Zone valve reports the connection state"
status: Obsolete
priority: High
owner: A. Hassan
parent: INFO-MS9DAG
order: 50
links:
  - type: verifies
    target: SYS-EPQX5G
    confirmed: 839c3250cb67
  - type: verifies
    target: SW-DGDM8Z
    confirmed: 073b39b4eae5
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
