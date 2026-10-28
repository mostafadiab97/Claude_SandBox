---
id: REQ-QS5SYX2
type: test-case
title: "Verify: Zigbee radio encrypts error conditions"
status: Approved
priority: High
owner: R. Nabil
tags:
  - connectivity
former-id: TC-NPYXKN
parent: REQ-67RQXCK
order: b0R
links:
  - type: verifies
    target: REQ-5PW0SDX
    confirmed: abf71e4c34db
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
