---
id: REQ-N6R2KKD
type: test-case
title: "Verify: Local API validates schedule entries"
status: Review
priority: Medium
owner: K. Tanaka
former-id: TC-KTSMC3
parent: REQ-67RQXCK
order: b0Q
links:
  - type: verifies
    target: REQ-PSTERQ0
    confirmed: 72a1d0da5245
  - type: verifies
    target: REQ-GC6WG48
    confirmed: 40e865bce9f5
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
