---
id: REQ-8MXJ5FC
type: test-case
title: "Verify: Mobile app notifys the room temperature"
status: Draft
priority: Low
tags:
  - release-1.0
  - accessibility
  - security
former-id: TC-WYBPXN
parent: REQ-WR5ZJN9
order: aW
links:
  - type: verifies
    target: REQ-T5AFT29
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
