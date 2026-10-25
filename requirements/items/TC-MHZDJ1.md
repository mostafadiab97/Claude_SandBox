---
id: TC-MHZDJ1
type: test-case
title: "Verify: Secure boot logs the operating mode"
status: Review
owner: K. Tanaka
parent: INFO-Z4TW4B
order: 1560
links:
  - type: verifies
    target: SYS-NQ8RXH
    confirmed: 372b9844dfa7
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
