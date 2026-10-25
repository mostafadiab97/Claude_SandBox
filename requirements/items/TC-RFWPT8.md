---
id: TC-RFWPT8
type: test-case
title: "Verify: Battery backup notifys the operating mode"
status: Approved
priority: Low
parent: INFO-MACGC3
order: 910
links:
  - type: verifies
    target: SYS-4JV7MY
    confirmed: 199fce62923b
  - type: verifies
    target: SW-C4TQ7V
    confirmed: 71eb8e44b2b0
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
