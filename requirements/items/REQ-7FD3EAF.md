---
id: REQ-7FD3EAF
type: test-case
title: "Verify: Battery backup encrypts sensor readings"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-HVBXDF
parent: REQ-F9Z1FYS
order: b1L
links:
  - type: verifies
    target: REQ-ZD15HFR
    confirmed: ecfbe5ff7471
  - type: verifies
    target: REQ-FKSN2AH
    confirmed: ef31d0e9d4d5
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
