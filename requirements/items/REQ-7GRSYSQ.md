---
id: TC-JH6NGD
type: test-case
title: "Verify: Encryption layer detects the operating mode"
status: Review
priority: High
owner: M. Farouk
parent: INFO-Z4TW4B
order: 1350
links:
  - type: verifies
    target: SYS-NA1SC7
    confirmed: 5bf0247d7ebd
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Switch error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
