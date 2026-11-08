---
id: REQ-N19EMQJ
type: test-case
title: "Verify: Boiler interface notifys user preferences"
status: Approved
owner: K. Tanaka
tags:
  - customer-request
  - accessibility
former-id: TC-JA7HA0
parent: REQ-XGWSK2K
order: b1P
links:
  - type: verifies
    target: REQ-DC7HJR1
    confirmed: 00d3546fe417
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
