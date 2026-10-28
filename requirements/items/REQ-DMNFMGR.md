---
id: REQ-DMNFMGR
type: test-case
title: "Verify: Login screen logs the operating mode"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - customer-request
former-id: TC-BPGCQM
parent: REQ-WR5ZJN9
order: b0K
links:
  - type: verifies
    target: REQ-GRZK4CZ
    confirmed: 6163aa570a7a
  - type: verifies
    target: REQ-65JZA9E
    confirmed: 5c7155c7a225
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
