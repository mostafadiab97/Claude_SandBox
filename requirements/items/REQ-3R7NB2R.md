---
id: REQ-3R7NB2R
type: test-case
title: "Verify: Zigbee radio restores firmware images"
status: Review
priority: High
owner: R. Nabil
tags:
  - cost
former-id: TC-3TBQPF
parent: REQ-67RQXCK
order: b01
links:
  - type: verifies
    target: REQ-QN6YX83
    confirmed: fb057a0da125
  - type: verifies
    target: REQ-25XBW9S
    confirmed: b739d638789a
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
