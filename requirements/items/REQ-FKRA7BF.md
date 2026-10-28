---
id: REQ-FKRA7BF
type: test-case
title: "Verify: Secure boot authenticates the set point"
status: Review
priority: High
tags:
  - cost
  - performance
former-id: TC-JWVRXM
parent: REQ-K6FGAY0
order: aV
links:
  - type: verifies
    target: REQ-E1MVNBB
    confirmed: 80942e0b2984
  - type: verifies
    target: REQ-42BTP6N
    confirmed: 650f794940e6
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
