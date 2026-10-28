---
id: REQ-XWDGWYA
type: test-case
title: "Verify: Zigbee radio measures the connection state"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - connectivity
  - performance
former-id: TC-B237F3
parent: REQ-67RQXCK
order: b16
links:
  - type: verifies
    target: REQ-774FTE6
    confirmed: aa7b6b73deff
  - type: verifies
    target: REQ-2YDTGM5
    confirmed: be1f80f82e4f
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
