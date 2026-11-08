---
id: REQ-ETQMQC7
type: test-case
title: "Verify: Encryption layer reports the room temperature"
status: Draft
priority: High
owner: R. Nabil
former-id: TC-7S4PHY
parent: REQ-K6FGAY0
order: aP
links:
  - type: verifies
    target: REQ-5RZXY01
    confirmed: 8b6fa0928d20
  - type: verifies
    target: REQ-7ZDJAAS
    confirmed: b023bd0bf70c
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
