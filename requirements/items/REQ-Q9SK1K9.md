---
id: REQ-Q9SK1K9
type: test-case
title: "Verify: Encryption layer encrypts the operating mode"
status: Approved
owner: L. Samir
tags:
  - customer-request
  - power
  - safety
former-id: TC-HP128S
parent: REQ-K6FGAY0
order: b0l
links:
  - type: verifies
    target: REQ-RT54X0B
    confirmed: 219ba032e325
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
