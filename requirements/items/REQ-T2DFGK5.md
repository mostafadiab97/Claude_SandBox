---
id: REQ-T2DFGK5
type: test-case
title: "Verify: OTA server logs schedule entries"
status: Approved
priority: High
owner: L. Samir
tags:
  - ux
  - cost
former-id: TC-BHHX0S
parent: REQ-8351896
order: aB
links:
  - type: verifies
    target: REQ-FWGAA5Z
    confirmed: b9c7a1a0e56b
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
