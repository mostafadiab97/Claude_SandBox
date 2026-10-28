---
id: TC-HP4Q0C
type: test-case
title: "Verify: Zone valve validates error conditions"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - connectivity
parent: INFO-MS9DAG
order: 240
links:
  - type: verifies
    target: SYS-7THG7S
    confirmed: c2a2db34ec62
  - type: verifies
    target: SW-WRPYK6
    confirmed: 54253c7ea624
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
