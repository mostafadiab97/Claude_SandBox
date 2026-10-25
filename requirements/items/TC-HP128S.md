---
id: TC-HP128S
type: test-case
title: "Verify: Encryption layer encrypts the operating mode"
status: Approved
owner: L. Samir
tags:
  - customer-request
  - power
  - safety
parent: INFO-Z4TW4B
order: 1100
links:
  - type: verifies
    target: SYS-TTBBAW
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
