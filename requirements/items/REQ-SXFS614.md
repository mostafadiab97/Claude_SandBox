---
id: REQ-SXFS614
type: test-case
title: "Verify: Status LED measures schedule entries"
status: Draft
priority: High
owner: M. Farouk
former-id: TC-D0502K
parent: REQ-Y9VHHKA
order: b0I
links:
  - type: verifies
    target: REQ-055THBY
    confirmed: 5ddece9ce40b
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
