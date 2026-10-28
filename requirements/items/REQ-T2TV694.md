---
id: REQ-T2TV694
type: test-case
title: "Verify: Zigbee radio authenticates relay events"
status: Approved
priority: High
owner: S. Adel
former-id: TC-YDNEYD
parent: REQ-67RQXCK
order: b0P
links:
  - type: verifies
    target: REQ-YYPX12F
    confirmed: 3d1d8edc4849
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
