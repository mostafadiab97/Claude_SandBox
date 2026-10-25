---
id: TC-803RWP
type: test-case
title: "Verify: Battery backup stores the room temperature"
status: Approved
priority: Medium
owner: N. Kamal
parent: INFO-MACGC3
order: 260
links:
  - type: verifies
    target: SYS-K2NWME
  - type: verifies
    target: SW-SV5WNT
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
