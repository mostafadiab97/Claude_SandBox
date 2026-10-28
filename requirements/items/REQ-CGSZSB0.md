---
id: REQ-CGSZSB0
type: test-case
title: "Verify: Login screen notifys energy consumption"
status: Obsolete
priority: Low
owner: N. Kamal
tags:
  - i18n
former-id: TC-B6BCG8
parent: REQ-WR5ZJN9
order: b0j
links:
  - type: verifies
    target: REQ-FWM1WC5
    confirmed: 62fe12aea17c
  - type: verifies
    target: REQ-8R81M1Y
    confirmed: 254e4c6d5905
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
