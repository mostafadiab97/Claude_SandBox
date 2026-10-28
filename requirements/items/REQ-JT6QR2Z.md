---
id: REQ-JT6QR2Z
type: test-case
title: "Verify: Tamper detection validates user preferences"
status: Draft
priority: High
owner: R. Nabil
former-id: TC-2M4SX3
parent: REQ-K6FGAY0
order: b0P
links:
  - type: verifies
    target: REQ-TZQDNSR
    confirmed: 7c077fec9862
  - type: verifies
    target: REQ-08SFWPE
    confirmed: 00c6a3ef7be5
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
