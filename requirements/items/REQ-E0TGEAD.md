---
id: REQ-E0TGEAD
type: test-case
title: "Verify: Zigbee radio switchs firmware images"
status: Draft
priority: High
owner: A. Hassan
tags:
  - performance
  - safety
former-id: TC-P187F1
parent: REQ-67RQXCK
order: ad
links:
  - type: verifies
    target: REQ-H0CKF26
    confirmed: e21c897550a0
  - type: verifies
    target: REQ-0D8BWEX
    confirmed: fce7af1ab815
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
