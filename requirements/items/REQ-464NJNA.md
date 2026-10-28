---
id: REQ-464NJNA
type: test-case
title: "Verify: Heating controller measures safety limits"
status: Approved
priority: High
former-id: TC-P7Q0F7
parent: REQ-XGWSK2K
order: b0D
links:
  - type: verifies
    target: REQ-BKYB8D1
    confirmed: 72056f4d9703
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Report user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
