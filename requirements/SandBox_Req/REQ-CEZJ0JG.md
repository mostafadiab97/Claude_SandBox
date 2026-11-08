---
id: REQ-CEZJ0JG
type: test-case
title: "Verify: Regulation loop limits safety limits"
status: Draft
priority: High
owner: N. Kamal
former-id: TC-ZMM0JQ
parent: REQ-XGWSK2K
order: b01
links:
  - type: verifies
    target: REQ-E1AFN5W
    confirmed: 982b55b41ef5
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
