---
id: REQ-GG7734R
type: test-case
title: "Verify: Encryption layer displays sensor readings"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
former-id: TC-AA7JGK
parent: REQ-K6FGAY0
order: b1O
links:
  - type: verifies
    target: REQ-RSNHK9N
    confirmed: 061c07f59466
  - type: verifies
    target: REQ-M4PXVBQ
    confirmed: 9a7c3b69032e
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
