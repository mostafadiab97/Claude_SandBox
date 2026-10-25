---
id: TC-NAV9NG
type: test-case
title: "Verify: Mobile app notifys humidity values"
status: Approved
priority: Low
owner: A. Hassan
parent: INFO-J0FETE
order: 1020
links:
  - type: verifies
    target: SYS-1A7QWR
  - type: verifies
    target: SW-5VFSCY
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Limit humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
