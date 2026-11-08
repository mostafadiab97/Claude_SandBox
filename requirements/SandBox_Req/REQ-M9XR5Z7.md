---
id: REQ-M9XR5Z7
type: test-case
title: "Verify: Secure boot synchronises audit records"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - release-2.0
  - accessibility
former-id: TC-PSQ7F2
parent: REQ-K6FGAY0
order: b1N
links:
  - type: verifies
    target: REQ-0KAWBJY
    confirmed: 2c023351a960
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
