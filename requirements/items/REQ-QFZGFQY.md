---
id: REQ-QFZGFQY
type: test-case
title: "Verify: Mobile app synchronises firmware images"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-ZPAYSJ
parent: REQ-WR5ZJN9
order: b0a
links:
  - type: verifies
    target: REQ-43JY6PF
    confirmed: 54d963c03420
  - type: verifies
    target: REQ-YMMXAK8
    confirmed: 2d0abae3753b
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
