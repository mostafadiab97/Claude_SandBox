---
id: REQ-TAZDDAQ
type: test-case
title: "Verify: Encryption layer measures the room temperature"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: TC-BA9XXR
parent: REQ-K6FGAY0
order: b0C
links:
  - type: verifies
    target: REQ-4KFD407
    confirmed: 83098b4942a6
  - type: verifies
    target: REQ-A7BN875
    confirmed: 9014314d84cc
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
