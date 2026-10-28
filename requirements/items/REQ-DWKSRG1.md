---
id: REQ-DWKSRG1
type: test-case
title: "Verify: Boiler interface switchs user preferences"
status: Review
priority: Medium
owner: L. Samir
former-id: TC-GKZTAB
parent: REQ-XGWSK2K
order: af
links:
  - type: verifies
    target: REQ-3E2Z93D
    confirmed: 051a9b0bce58
  - type: verifies
    target: REQ-10R1WW9
    confirmed: e433c3217e25
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
