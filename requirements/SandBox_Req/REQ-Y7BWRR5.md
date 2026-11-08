---
id: REQ-Y7BWRR5
type: test-case
title: "Verify: Encryption layer limits humidity values"
status: Review
priority: Medium
owner: L. Samir
former-id: TC-N8DA8A
parent: REQ-K6FGAY0
order: a1
links:
  - type: verifies
    target: REQ-YC34KJR
    confirmed: b4b9539a5d88
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
