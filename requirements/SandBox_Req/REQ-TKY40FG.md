---
id: REQ-TKY40FG
type: test-case
title: "Verify: Encryption layer logs user preferences"
status: Draft
priority: High
owner: S. Adel
former-id: TC-YW2W19
parent: REQ-K6FGAY0
order: b1D
links:
  - type: verifies
    target: REQ-DM2TR54
    confirmed: e469f30b51d1
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
