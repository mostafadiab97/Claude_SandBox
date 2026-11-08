---
id: REQ-D1KVT99
type: test-case
title: "Verify: Zigbee radio restores firmware images"
status: Obsolete
owner: محمد علي
former-id: TC-5D4A6Q
parent: REQ-67RQXCK
order: ar
links:
  - type: verifies
    target: REQ-2Y6ZD88
    confirmed: 36bbc40bd419
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Validate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
