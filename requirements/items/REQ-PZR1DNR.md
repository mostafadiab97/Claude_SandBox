---
id: REQ-PZR1DNR
type: test-case
title: "Verify: Mobile app authenticates relay events"
status: Draft
priority: Low
owner: S. Adel
former-id: TC-6JGA6A
parent: REQ-WR5ZJN9
order: b01
links:
  - type: verifies
    target: REQ-94M0JBB
    confirmed: 545c48596828
  - type: verifies
    target: REQ-X1RW2P6
    confirmed: 14014a8e9ebe
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
