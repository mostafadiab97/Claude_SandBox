---
id: REQ-T1BF2XT
type: test-case
title: "Verify: Regulation loop stores energy consumption"
status: Draft
priority: Low
owner: Y. Saber
former-id: TC-D5A27K
parent: REQ-XGWSK2K
order: b0e
links:
  - type: verifies
    target: REQ-YBTYEC4
    confirmed: 2c4d5f93b13d
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
