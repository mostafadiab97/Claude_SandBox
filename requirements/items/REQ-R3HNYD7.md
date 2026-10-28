---
id: REQ-R3HNYD7
type: test-case
title: "Verify: Tamper detection validates safety limits"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - cost
former-id: TC-BHBGV4
parent: REQ-K6FGAY0
order: aO
links:
  - type: verifies
    target: REQ-KBZR5EK
    confirmed: 0b387183e7b1
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Authenticate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
