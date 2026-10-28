---
id: REQ-E4B1RXR
type: test-case
title: "Verify: Wi-Fi module synchronises sensor readings"
status: Approved
former-id: TC-2JBGRT
parent: REQ-67RQXCK
order: as
links:
  - type: verifies
    target: REQ-A2XPEJG
    confirmed: 306846e9f601
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
