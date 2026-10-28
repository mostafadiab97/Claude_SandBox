---
id: REQ-NMFZPHD
type: test-case
title: "Verify: Wi-Fi module authenticates the operating mode"
status: Draft
priority: Low
owner: R. Nabil
former-id: TC-F0AJ40
parent: REQ-67RQXCK
order: b0o
links:
  - type: verifies
    target: REQ-NXTCN67
    confirmed: 5e996d12a800
  - type: verifies
    target: REQ-TY56HQC
    confirmed: 93d7e93dc0c5
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
