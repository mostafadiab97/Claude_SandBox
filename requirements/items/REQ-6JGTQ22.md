---
id: REQ-6JGTQ22
type: test-case
title: "Verify: Boiler interface displays firmware images"
status: Review
priority: High
owner: É. Laurent
former-id: TC-51GFSD
parent: REQ-XGWSK2K
order: b1A
links:
  - type: verifies
    target: REQ-95STN6W
    confirmed: 7dfb91f535ef
  - type: verifies
    target: REQ-0CW7N9N
    confirmed: 3119f0b6b4c8
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
