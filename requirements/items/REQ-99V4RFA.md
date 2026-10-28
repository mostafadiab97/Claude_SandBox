---
id: REQ-99V4RFA
type: test-case
title: "Verify: Heating controller notifys relay events"
status: Review
priority: Low
owner: L. Samir
former-id: TC-JVAAQY
parent: REQ-XGWSK2K
order: ao
links:
  - type: verifies
    target: REQ-YBS8MW9
    confirmed: 8158ead818f6
  - type: verifies
    target: REQ-X1GZ3E9
    confirmed: b4c2cec05ff8
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
