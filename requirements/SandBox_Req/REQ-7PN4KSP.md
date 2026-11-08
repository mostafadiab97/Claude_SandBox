---
id: REQ-7PN4KSP
type: test-case
title: "Verify: Login screen notifys the room temperature"
status: Review
priority: Low
owner: A. Hassan
tags:
  - performance
  - accessibility
former-id: TC-B02MZ1
parent: REQ-WR5ZJN9
order: aU
links:
  - type: verifies
    target: REQ-4GW7FRK
    confirmed: 77747505e6c0
  - type: verifies
    target: REQ-VYBJ4R5
    confirmed: ca2b2e2e8bb1
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Restore the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
