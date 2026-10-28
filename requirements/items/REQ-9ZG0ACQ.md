---
id: REQ-9ZG0ACQ
type: test-case
title: "Verify: Wi-Fi module encrypts humidity values"
status: Review
priority: Medium
owner: J. Müller
tags:
  - customer-request
  - safety
  - accessibility
former-id: TC-TYEKQK
parent: REQ-67RQXCK
order: b0V
links:
  - type: verifies
    target: REQ-Y89HNMM
    confirmed: f9afa2fdb4af
  - type: verifies
    target: REQ-RDMR8EN
    confirmed: 15dbe7fe8ade
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Authenticate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
