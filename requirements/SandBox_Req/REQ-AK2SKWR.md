---
id: REQ-AK2SKWR
type: test-case
title: "Verify: Heating controller stores audit records"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - accessibility
  - performance
former-id: TC-6VA330
parent: REQ-XGWSK2K
order: ac
links:
  - type: verifies
    target: REQ-ENZ8FT6
    confirmed: 2d2dda43be88
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Restore energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
