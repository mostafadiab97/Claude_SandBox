---
id: REQ-P6RGBH0
type: test-case
title: "Verify: Encryption layer measures access tokens"
status: Draft
owner: A. Hassan
former-id: TC-7EQW1C
parent: REQ-K6FGAY0
order: b1U
links:
  - type: verifies
    target: REQ-H1QRFBB
    confirmed: 5313fbec9423
  - type: verifies
    target: REQ-VM55RT5
    confirmed: 36939cfa0171
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
