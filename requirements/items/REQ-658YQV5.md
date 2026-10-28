---
id: REQ-658YQV5
type: test-case
title: "Verify: Heating controller detects sensor readings"
status: Review
priority: Medium
owner: Y. Saber
tags:
  - i18n
former-id: TC-7YD8MD
parent: REQ-XGWSK2K
order: aW
links:
  - type: verifies
    target: REQ-Y8A0W34
    confirmed: 9687363c0226
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
