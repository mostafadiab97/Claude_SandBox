---
id: REQ-D66FVA3
type: test-case
title: "Verify: Wi-Fi module authenticates the room temperature"
status: Approved
priority: Medium
owner: Y. Saber
former-id: TC-J1QQWT
parent: REQ-67RQXCK
order: b14
links:
  - type: verifies
    target: REQ-GHJK43J
    confirmed: a8274ea6218e
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
