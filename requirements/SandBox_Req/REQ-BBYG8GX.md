---
id: REQ-BBYG8GX
type: test-case
title: "Verify: Boiler interface validates schedule entries"
status: Review
priority: Medium
owner: L. Samir
former-id: TC-C9G5AT
parent: REQ-XGWSK2K
order: b0o
links:
  - type: verifies
    target: REQ-S85HGV0
    confirmed: 665acc28f34d
  - type: verifies
    target: REQ-X1GZ3E9
    confirmed: b4c2cec05ff8
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
