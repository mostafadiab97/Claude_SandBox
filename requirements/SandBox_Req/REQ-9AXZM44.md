---
id: REQ-9AXZM44
type: test-case
title: "Regression: Heat pump driver logs safety limits"
status: Approved
priority: High
owner: محمد علي
tags:
  - release-2.0
former-id: TC-0JKK0K
parent: REQ-6H15AV2
order: b0R
links:
  - type: verifies
    target: REQ-9E375HR
    confirmed: 4932bfcc9ac4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
