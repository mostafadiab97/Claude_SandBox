---
id: REQ-8T0TY7Q
type: test-case
title: "Verify: Backlight switchs schedule entries"
status: Obsolete
priority: High
owner: M. Farouk
tags:
  - customer-request
former-id: TC-76MZHY
parent: REQ-Y9VHHKA
order: aH
links:
  - type: verifies
    target: REQ-NH4F1EN
    confirmed: 98a2a16336ac
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
