---
id: REQ-W1BHB0Y
type: test-case
title: "Verify: Secure boot synchronises energy consumption"
status: Review
priority: Medium
owner: J. Müller
tags:
  - release-2.0
  - release-1.0
  - performance
former-id: TC-HH5K99
parent: REQ-K6FGAY0
order: al
links:
  - type: verifies
    target: REQ-VCHHJMJ
    confirmed: 60302e1ca7b2
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
