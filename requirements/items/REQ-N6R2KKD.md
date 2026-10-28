---
id: TC-KTSMC3
type: test-case
title: "Verify: Local API validates schedule entries"
status: Review
priority: Medium
owner: K. Tanaka
parent: INFO-F0M7VC
order: 890
links:
  - type: verifies
    target: SYS-EJ6VGS
    confirmed: 72a1d0da5245
  - type: verifies
    target: SW-GBZD65
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
