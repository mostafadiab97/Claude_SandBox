---
id: REQ-24HZ1AR
type: test-case
title: "Verify: Mobile app restores access tokens"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - EMC
  - i18n
  - release-1.0
former-id: TC-6QK171
parent: REQ-WR5ZJN9
order: b1T
links:
  - type: verifies
    target: REQ-K2S78AW
    confirmed: 9375eb52bc71
  - type: verifies
    target: REQ-PDF7ZFK
    confirmed: affe143fc077
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
