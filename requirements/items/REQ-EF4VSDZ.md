---
id: REQ-EF4VSDZ
type: test-case
title: "Verify: Mobile app logs audit records"
status: Approved
priority: Medium
owner: R. Nabil
former-id: TC-TAQ8E2
parent: REQ-WR5ZJN9
order: b0t
links:
  - type: verifies
    target: REQ-QCTQNWF
    confirmed: 7688feffffa3
  - type: verifies
    target: REQ-SHPD9A7
    confirmed: bece0b29d288
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
