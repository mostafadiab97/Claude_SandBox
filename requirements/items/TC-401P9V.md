---
id: TC-401P9V
type: test-case
title: "Verify: Battery backup stores the room temperature"
status: Obsolete
priority: High
owner: L. Samir
parent: INFO-MACGC3
order: 930
links:
  - type: verifies
    target: SYS-1T0TAM
    confirmed: 834d1bdeda5b
  - type: verifies
    target: SW-KDMQZE
    confirmed: 1bae33046337
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
