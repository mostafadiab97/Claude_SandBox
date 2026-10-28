---
id: REQ-8NGVP88
type: test-case
title: "Verify: Wi-Fi module detects schedule entries"
status: Approved
priority: High
owner: J. Müller
tags:
  - regulatory
  - i18n
former-id: TC-Q0E7GZ
parent: REQ-67RQXCK
order: b0H
links:
  - type: verifies
    target: REQ-K15JQP3
    confirmed: da5ffbb2dc98
  - type: verifies
    target: REQ-Z8TBDTM
    confirmed: 7f592a075c3f
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
