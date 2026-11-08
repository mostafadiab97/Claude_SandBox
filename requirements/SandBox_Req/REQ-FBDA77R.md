---
id: REQ-FBDA77R
type: test-case
title: "Verify: Wi-Fi module notifys the room temperature"
status: Review
priority: Low
owner: S. Adel
tags:
  - accessibility
  - ux
former-id: TC-78BAHG
parent: REQ-67RQXCK
order: aa
links:
  - type: verifies
    target: REQ-JNHH86M
    confirmed: 8a99ad0fb5ef
  - type: verifies
    target: REQ-NWRBETP
    confirmed: beec846c8c19
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
