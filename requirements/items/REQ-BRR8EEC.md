---
id: REQ-BRR8EEC
type: test-case
title: "Verify: Secure boot switchs the set point"
status: Approved
priority: Medium
owner: M. Farouk
former-id: TC-0277BP
parent: REQ-K6FGAY0
order: aX
links:
  - type: verifies
    target: REQ-G4RKHEY
    confirmed: 6b7150a5bc62
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
