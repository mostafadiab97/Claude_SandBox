---
id: REQ-WRPZQV6
type: test-case
title: "Verify: Heat pump driver logs safety limits"
status: Review
priority: Medium
former-id: TC-EKWE21
parent: REQ-XGWSK2K
order: b0X
links:
  - type: verifies
    target: REQ-9E375HR
    confirmed: 4932bfcc9ac4
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
