---
id: REQ-NENZGEN
type: test-case
title: "Verify: Encryption layer encrypts schedule entries"
status: Obsolete
priority: Medium
owner: H. Mostafa
former-id: TC-F7M5CV
parent: REQ-K6FGAY0
order: b0d
links:
  - type: verifies
    target: REQ-R4BZZKT
    confirmed: c9ae9a4debf3
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
