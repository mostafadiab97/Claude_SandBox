---
id: REQ-BJDEGWY
type: test-case
title: "Verify: Secure boot limits safety limits"
status: Review
priority: Medium
owner: Y. Saber
former-id: TC-7PR1Y2
parent: REQ-K6FGAY0
order: aM
links:
  - type: verifies
    target: REQ-RNCD05K
    confirmed: 243ec13ec9e6
  - type: verifies
    target: REQ-NV41NQC
    confirmed: bff4a0ed5836
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
