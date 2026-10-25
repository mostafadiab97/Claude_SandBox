---
id: TC-P2RBER
type: test-case
title: "Verify: Zone valve switchs error conditions"
status: Draft
priority: High
owner: محمد علي
parent: INFO-MS9DAG
order: 1400
links:
  - type: verifies
    target: SYS-FMGH3F
    confirmed: 3b65dd538b13
  - type: verifies
    target: SW-CD64BA
    confirmed: f7be308643e4
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
