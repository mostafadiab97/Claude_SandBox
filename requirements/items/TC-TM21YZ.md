---
id: TC-TM21YZ
type: test-case
title: "Verify: Battery backup limits safety limits"
status: Obsolete
priority: Medium
owner: N. Kamal
parent: INFO-MACGC3
order: 1540
links:
  - type: verifies
    target: SYS-SA1DH7
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
