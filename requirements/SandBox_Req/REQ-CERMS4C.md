---
id: REQ-CERMS4C
type: test-case
title: "Verify: Mobile app switchs sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - connectivity
  - accessibility
former-id: TC-G7MBV1
parent: REQ-WR5ZJN9
order: aI
links:
  - type: verifies
    target: REQ-6CNE4KJ
    confirmed: 16f3ad7fdfaa
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
