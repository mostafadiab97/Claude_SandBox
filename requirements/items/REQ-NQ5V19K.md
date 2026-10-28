---
id: REQ-NQ5V19K
type: test-case
title: "Verify: Zigbee radio switchs safety limits"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - safety
former-id: TC-GJ1HVK
parent: REQ-67RQXCK
order: b1C
links:
  - type: verifies
    target: REQ-MSN5XXC
    confirmed: 1917153ef15c
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
