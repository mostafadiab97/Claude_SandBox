---
id: TC-78BAHG
type: test-case
title: "Verify: Wi-Fi module notifys the room temperature"
status: Review
priority: Low
owner: S. Adel
tags:
  - accessibility
  - ux
parent: INFO-F0M7VC
order: 370
links:
  - type: verifies
    target: SYS-91NRJ9
  - type: verifies
    target: SW-J6NQD8
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
