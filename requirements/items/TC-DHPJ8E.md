---
id: TC-DHPJ8E
type: test-case
title: "Verify: Over-temperature monitor switchs safety limits"
status: Approved
priority: Low
owner: H. Mostafa
tags:
  - connectivity
  - safety
parent: INFO-Z4TW4B
order: 1320
links:
  - type: verifies
    target: SYS-BY1F6D
    confirmed: 47a415e5df93
  - type: verifies
    target: SW-ZZMBEM
    confirmed: d4c7a4c96ca5
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
