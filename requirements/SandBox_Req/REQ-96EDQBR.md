---
id: REQ-96EDQBR
type: test-case
title: "Verify: Regulation loop calibrates the room temperature"
status: Approved
priority: High
former-id: TC-TP8GMD
parent: REQ-XGWSK2K
order: b0n
links:
  - type: verifies
    target: REQ-FWFRZ9W
    confirmed: 4fabc5aa13e6
  - type: verifies
    target: REQ-C58NWQ8
    confirmed: 54e0e57fc0f2
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
