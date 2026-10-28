---
id: REQ-FAZ8FBZ
type: test-case
title: "Verify: Login screen encrypts error conditions"
status: Draft
owner: Y. Saber
tags:
  - release-2.0
  - i18n
former-id: TC-1YPJSW
parent: REQ-WR5ZJN9
order: aE
links:
  - type: verifies
    target: REQ-CCRB185
    confirmed: 4c561d45744d
  - type: verifies
    target: REQ-71BWGG7
    confirmed: 48866ed0074a
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
