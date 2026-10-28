---
id: REQ-5GSR3P0
type: test-case
title: "Verify: Zigbee radio displays safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: TC-ZE7GTA
parent: REQ-67RQXCK
order: aD
links:
  - type: verifies
    target: REQ-C7QGA19
    confirmed: dfc6c8083c05
  - type: verifies
    target: REQ-WVSG698
    confirmed: 0448e6c3fca0
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
