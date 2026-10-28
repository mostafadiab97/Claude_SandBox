---
id: REQ-XWPMXE7
type: test-case
title: "Verify: Regulation loop switchs the room temperature"
status: Obsolete
priority: High
owner: K. Tanaka
former-id: TC-6EYKE4
parent: REQ-XGWSK2K
order: b1C
links:
  - type: verifies
    target: REQ-DZ4NZB2
    confirmed: 51ed09f00e1d
  - type: verifies
    target: REQ-X2QFS3T
    confirmed: 2f356afe5198
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
