---
id: TC-FE2FJZ
type: test-case
title: "Verify: Pairing process notifys the connection state"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - customer-request
  - ux
  - connectivity
parent: INFO-F0M7VC
order: 990
links:
  - type: verifies
    target: SYS-ZH89V8
    confirmed: 777482c845de
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
