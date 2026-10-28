---
id: REQ-1YF6BQY
type: test-case
title: "Verify: Wi-Fi module validates humidity values"
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - security
  - cost
former-id: TC-4Z6GVE
parent: REQ-67RQXCK
order: b17
links:
  - type: verifies
    target: REQ-Y5TQ0M6
    confirmed: d32333e735ba
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
