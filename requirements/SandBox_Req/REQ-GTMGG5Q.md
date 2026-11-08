---
id: REQ-GTMGG5Q
type: test-case
title: "Regression: Heating controller measures safety limits"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - connectivity
  - i18n
former-id: TC-GKX6G2
parent: REQ-6H15AV2
order: b13
links:
  - type: verifies
    target: REQ-BKYB8D1
    confirmed: 04e59d900da3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
