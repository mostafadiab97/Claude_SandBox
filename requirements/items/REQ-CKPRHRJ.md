---
id: REQ-CKPRHRJ
type: test-case
title: "Verify: Encryption layer authenticates humidity values"
status: Draft
priority: Medium
owner: محمد علي
former-id: TC-ZWEGMJ
parent: REQ-K6FGAY0
order: af
links:
  - type: verifies
    target: REQ-2ZR5V0B
    confirmed: cfe3f145e294
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
