---
id: TC-KGPGWV
type: test-case
title: "Verify: Zone valve calibrates relay events"
status: Obsolete
priority: Medium
owner: S. Adel
parent: INFO-MS9DAG
order: 70
links:
  - type: verifies
    target: SYS-8Q3CHA
  - type: verifies
    target: SW-2TBDPG
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
