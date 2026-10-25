---
id: TC-EPQAH9
type: test-case
title: "Verify: Zone valve logs the operating mode"
status: Draft
priority: Medium
parent: INFO-MS9DAG
order: 1480
links:
  - type: verifies
    target: SYS-WQ0CE1
    confirmed: 876eb172799e
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
