---
id: REQ-R21GWJ6
type: test-case
title: "Verify: Wi-Fi module stores access tokens"
status: Approved
owner: H. Mostafa
former-id: TC-CBJ5AB
parent: REQ-67RQXCK
order: b15
links:
  - type: verifies
    target: REQ-4JCY9Z0
    confirmed: 443125a88fee
  - type: verifies
    target: REQ-XQ2M1N7
    confirmed: 781c13a755cb
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
