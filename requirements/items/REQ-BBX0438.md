---
id: REQ-BBX0438
type: test-case
title: "Verify: Encryption layer authenticates the operating mode"
status: Review
priority: Medium
owner: H. Mostafa
former-id: TC-DAY0F3
parent: REQ-K6FGAY0
order: b1P
links:
  - type: verifies
    target: REQ-0A641HY
    confirmed: 9748f881870f
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
