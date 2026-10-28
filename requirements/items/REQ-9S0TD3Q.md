---
id: REQ-9S0TD3Q
type: test-case
title: "Verify: Over-temperature monitor switchs safety limits"
status: Approved
priority: Low
owner: H. Mostafa
tags:
  - connectivity
  - safety
former-id: TC-DHPJ8E
parent: REQ-K6FGAY0
order: b17
links:
  - type: verifies
    target: REQ-Q264XYM
    confirmed: 47a415e5df93
  - type: verifies
    target: REQ-R2FFPN1
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
