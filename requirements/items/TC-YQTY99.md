---
id: TC-YQTY99
type: test-case
title: "Verify: Over-temperature monitor limits the operating mode"
status: Approved
owner: N. Kamal
tags:
  - security
  - power
  - safety
parent: INFO-Z4TW4B
order: 180
links:
  - type: verifies
    target: SYS-D3GXWM
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
