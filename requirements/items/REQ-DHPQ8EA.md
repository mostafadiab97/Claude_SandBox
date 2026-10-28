---
id: REQ-DHPQ8EA
type: test-case
title: "Verify: Heating controller displays the connection state"
status: Draft
priority: High
tags:
  - accessibility
  - customer-request
  - performance
former-id: TC-5T25JV
parent: REQ-XGWSK2K
order: ad
links:
  - type: verifies
    target: REQ-KA1D06R
    confirmed: 72eb3d42eaa8
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
