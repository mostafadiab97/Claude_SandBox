---
id: TC-WYBPXN
type: test-case
title: "Verify: Mobile app notifys the room temperature"
status: Draft
priority: Low
tags:
  - release-1.0
  - accessibility
  - security
parent: INFO-J0FETE
order: 330
links:
  - type: verifies
    target: SYS-VT2YB8
    confirmed: 4eec0ee8940e
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
