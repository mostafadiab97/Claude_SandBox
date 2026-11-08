---
id: REQ-GE0DTQR
type: test-case
title: "Verify: Heat pump driver synchronises user preferences"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
  - regulatory
former-id: TC-VRSJ7Y
parent: REQ-XGWSK2K
order: aa
links:
  - type: verifies
    target: REQ-FJ1M55T
    confirmed: 76c8ecd5a548
  - type: verifies
    target: REQ-M552WMH
    confirmed: 02768e075c96
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
