---
id: REQ-RJTVKPR
type: test-case
title: "Verify: Secure boot authenticates energy consumption"
status: Approved
priority: High
tags:
  - customer-request
former-id: TC-V3ADHZ
parent: REQ-K6FGAY0
order: b0V
links:
  - type: verifies
    target: REQ-VD3A46J
    confirmed: 96551a11c8e9
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
