---
id: REQ-PQ3X1SA
type: test-case
title: "Verify: Over-temperature monitor notifys firmware images"
status: Draft
tags:
  - customer-request
former-id: TC-M4J6MT
parent: REQ-K6FGAY0
order: aD
links:
  - type: verifies
    target: REQ-MHAMGQ2
    confirmed: 877e6818b0de
  - type: verifies
    target: REQ-3DBXTZY
    confirmed: ae495b06e801
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Synchronise firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
