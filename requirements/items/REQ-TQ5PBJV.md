---
id: REQ-TQ5PBJV
type: test-case
title: "Verify: Pairing process measures access tokens"
status: Review
priority: Medium
owner: Y. Saber
tags:
  - i18n
former-id: TC-4Z660Q
parent: REQ-67RQXCK
order: aV
links:
  - type: verifies
    target: REQ-RRDNXJT
    confirmed: b0be1ee04270
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
