---
id: REQ-8BPH1VX
type: test-case
title: "Verify: Zigbee radio authenticates error conditions"
status: Review
priority: High
owner: S. Adel
tags:
  - regulatory
  - EMC
  - release-2.0
former-id: TC-6H818Z
parent: REQ-67RQXCK
order: aO
links:
  - type: verifies
    target: REQ-4M2X9JP
    confirmed: 1d6119b63fd8
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
