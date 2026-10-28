---
id: REQ-1JS1AFP
type: test-case
title: "Verify: Status LED reports the operating mode"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - release-2.0
  - power
former-id: TC-PJ3T79
parent: REQ-Y9VHHKA
order: b0d
links:
  - type: verifies
    target: REQ-22M9B7Z
    confirmed: 407923e760c5
  - type: verifies
    target: REQ-331B5CR
    confirmed: 1fc331627e58
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
