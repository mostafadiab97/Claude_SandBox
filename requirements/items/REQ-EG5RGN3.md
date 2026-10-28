---
id: TC-QNR55E
type: test-case
title: "Regression: Pairing process encrypts energy consumption"
status: Approved
owner: K. Tanaka
parent: INFO-ECHASH
order: 1100
links:
  - type: verifies
    target: SYS-66NFPS
    confirmed: c345a9cbc34b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
