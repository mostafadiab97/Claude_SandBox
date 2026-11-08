---
id: REQ-FAE11J9
type: test-case
title: "Verify: Wi-Fi module stores sensor readings"
status: Approved
priority: Medium
owner: L. Samir
former-id: TC-8AACCZ
parent: REQ-67RQXCK
order: at
links:
  - type: verifies
    target: REQ-WK5920T
    confirmed: e694361bd48d
  - type: verifies
    target: REQ-WHTZWSZ
    confirmed: 86644ed6fccb
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
