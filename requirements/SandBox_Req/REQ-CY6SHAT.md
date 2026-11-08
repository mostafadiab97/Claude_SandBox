---
id: REQ-CY6SHAT
type: test-case
title: "Verify: Boiler interface stores audit records"
status: Approved
tags:
  - customer-request
former-id: TC-GHYMVV
parent: REQ-XGWSK2K
order: am
links:
  - type: verifies
    target: REQ-T1AHZJK
    confirmed: 06bc752da75c
  - type: verifies
    target: REQ-JV3FCEW
    confirmed: 4a784bcd2cf6
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
