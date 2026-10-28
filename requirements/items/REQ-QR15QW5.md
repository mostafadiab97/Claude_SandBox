---
id: REQ-QR15QW5
type: test-case
title: "Verify: Zigbee radio authenticates the room temperature"
status: Approved
priority: Medium
tags:
  - EMC
  - i18n
  - power
former-id: TC-XAGXXQ
parent: REQ-67RQXCK
order: aA
links:
  - type: verifies
    target: REQ-H09Y5DF
    confirmed: 6499795c1519
  - type: verifies
    target: REQ-HBBBDNN
    confirmed: c8866c781995
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
