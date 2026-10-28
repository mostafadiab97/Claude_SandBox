---
id: REQ-TYGXW40
type: test-case
title: "Verify: Zigbee radio notifys the room temperature"
status: Approved
priority: High
former-id: TC-SDRMF5
parent: REQ-67RQXCK
order: b1A
links:
  - type: verifies
    target: REQ-0XRM35H
    confirmed: 3a34a02e68b2
  - type: verifies
    target: REQ-XG1EV4G
    confirmed: 9d2451409e8c
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
