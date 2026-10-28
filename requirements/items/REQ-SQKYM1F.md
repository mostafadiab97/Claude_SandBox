---
id: REQ-SQKYM1F
type: test-case
title: "Regression: Mobile app restores access tokens"
status: Draft
priority: High
owner: J. Müller
tags:
  - i18n
former-id: TC-PH812X
parent: REQ-6H15AV2
order: b0u
links:
  - type: verifies
    target: REQ-K2S78AW
    confirmed: 9375eb52bc71
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
