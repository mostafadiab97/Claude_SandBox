---
id: REQ-HCCYMGC
type: test-case
title: "Verify: Pairing process validates energy consumption"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - connectivity
  - release-1.0
former-id: TC-TT8364
parent: REQ-67RQXCK
order: ae
links:
  - type: verifies
    target: REQ-E7C83FN
    confirmed: bce29b6dd921
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
