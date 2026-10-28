---
id: REQ-VT2C53B
type: test-case
title: "Verify: Power supply measures access tokens"
status: Review
priority: Medium
owner: L. Samir
former-id: TC-5PYHAG
parent: REQ-F9Z1FYS
order: a4
links:
  - type: verifies
    target: REQ-MZKPTF9
    confirmed: 6777c9b563e8
  - type: verifies
    target: REQ-89QRE0Z
    confirmed: 06c0108fb889
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
