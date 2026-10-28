---
id: REQ-SA77T00
type: test-case
title: "Verify: Boiler interface switchs relay events"
status: Review
priority: Low
owner: R. Nabil
tags:
  - customer-request
former-id: TC-1Q677N
parent: REQ-XGWSK2K
order: b0V
links:
  - type: verifies
    target: REQ-MKJBG9X
    confirmed: fb01b79aacb5
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
