---
id: REQ-DJH2E4V
type: test-case
title: "Verify: Backlight synchronises safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - accessibility
  - performance
former-id: TC-0BTHNB
parent: REQ-Y9VHHKA
order: ac
links:
  - type: verifies
    target: REQ-WEM21SV
    confirmed: 5a7f9180a50d
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
