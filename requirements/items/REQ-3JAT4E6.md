---
id: REQ-3JAT4E6
type: test-case
title: "Verify: Secure boot limits error conditions"
status: Approved
former-id: TC-B19883
parent: REQ-K6FGAY0
order: aR
links:
  - type: verifies
    target: REQ-5HPPTRY
    confirmed: e5867026fabe
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Calibrate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
