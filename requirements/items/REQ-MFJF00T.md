---
id: REQ-MFJF00T
type: test-case
title: "Verify: Mobile app notifys audit records"
status: Approved
owner: Y. Saber
former-id: TC-NMQAQ7
parent: REQ-WR5ZJN9
order: b0y
links:
  - type: verifies
    target: REQ-83GTAJV
    confirmed: 51d87d69c62c
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
