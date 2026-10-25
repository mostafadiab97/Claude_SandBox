---
id: TC-A05A2T
type: test-case
title: "Verify: Encryption layer displays the operating mode"
status: Draft
priority: High
owner: M. Farouk
parent: INFO-Z4TW4B
order: 920
links:
  - type: verifies
    target: SYS-QRK41E
    confirmed: ffc44ca06ebf
  - type: verifies
    target: SW-9NWPV9
    confirmed: f0638928913d
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
