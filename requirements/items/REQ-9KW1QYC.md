---
id: REQ-9KW1QYC
type: test-case
title: "Verify: Regulation loop measures access tokens"
status: Obsolete
priority: Medium
owner: É. Laurent
tags:
  - release-2.0
former-id: TC-B5N1TK
parent: REQ-XGWSK2K
order: b0Q
links:
  - type: verifies
    target: REQ-ZM76EGY
    confirmed: 0c11557d1e86
  - type: verifies
    target: REQ-ZX039CQ
    confirmed: 6c24b6afc923
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
