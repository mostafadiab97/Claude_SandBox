---
id: REQ-6RD0PJ9
type: test-case
title: "Verify: Zone valve measures the connection state"
status: Review
owner: M. Farouk
former-id: TC-V2NG4D
parent: REQ-XGWSK2K
order: a7
links:
  - type: verifies
    target: REQ-1AQ8AT5
    confirmed: b42a1b2bb89f
  - type: verifies
    target: REQ-M552WMH
    confirmed: 02768e075c96
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
