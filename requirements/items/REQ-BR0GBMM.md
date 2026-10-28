---
id: REQ-BR0GBMM
type: test-case
title: "Verify: Secure boot synchronises schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - EMC
  - regulatory
former-id: TC-N4AM6S
parent: REQ-K6FGAY0
order: b1Q
links:
  - type: verifies
    target: REQ-6MEBSJR
    confirmed: b28f6844e565
  - type: verifies
    target: REQ-QPPQ2N3
    confirmed: 92e32f70136c
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
