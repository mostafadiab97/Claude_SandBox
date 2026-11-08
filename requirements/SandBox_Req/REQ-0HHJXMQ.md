---
id: REQ-0HHJXMQ
type: test-case
title: "Verify: Cloud backend switchs error conditions"
status: Review
tags:
  - ux
  - cost
  - customer-request
former-id: TC-TQ0KN5
parent: REQ-8351896
order: b0g
links:
  - type: verifies
    target: REQ-V6198RX
    confirmed: 4d23af5c0f84
  - type: verifies
    target: REQ-WHHNA6S
    confirmed: 4509eef2439a
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
