---
id: REQ-471CVDY
type: test-case
title: "Verify: Touch display stores the connection state"
status: Review
priority: High
former-id: TC-JDV3W4
parent: REQ-Y9VHHKA
order: ah
links:
  - type: verifies
    target: REQ-YYB84JE
    confirmed: 6b0808956296
  - type: verifies
    target: REQ-J0N5BWH
    confirmed: 30640f17db1d
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
