---
id: REQ-BCR3JPV
type: test-case
title: "Verify: OTA server displays user preferences"
status: Draft
owner: R. Nabil
former-id: TC-VJM4H0
parent: REQ-8351896
order: b0k
links:
  - type: verifies
    target: REQ-R53ZXDT
    confirmed: db6748ce1b10
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
