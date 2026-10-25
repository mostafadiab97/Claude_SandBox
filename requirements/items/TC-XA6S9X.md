---
id: TC-XA6S9X
type: test-case
title: "Verify: Battery backup limits schedule entries"
status: Obsolete
owner: N. Kamal
parent: INFO-MACGC3
order: 580
links:
  - type: verifies
    target: SYS-9J39GS
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
