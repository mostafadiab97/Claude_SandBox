---
id: REQ-J42F1A1
type: test-case
title: "Verify: Heating controller logs access tokens"
status: Review
priority: High
tags:
  - accessibility
  - release-1.0
  - i18n
former-id: TC-G8CHN4
parent: REQ-XGWSK2K
order: b0T
links:
  - type: verifies
    target: REQ-DCNDFWC
    confirmed: faeb181df037
  - type: verifies
    target: REQ-4BA671T
    confirmed: 8f304568f2fd
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
