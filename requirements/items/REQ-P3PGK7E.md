---
id: REQ-P3PGK7E
type: test-case
title: "Verify: OTA server logs the connection state"
status: Draft
priority: Medium
owner: M. Farouk
former-id: TC-NSP0AR
parent: REQ-8351896
order: b12
links:
  - type: verifies
    target: REQ-2EFA4DF
    confirmed: 2363be236978
  - type: verifies
    target: REQ-FPKDC3K
    confirmed: afa2f9924712
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
