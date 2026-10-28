---
id: REQ-C1VTA86
type: test-case
title: "Verify: Zone valve encrypts humidity values"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - power
  - release-1.0
former-id: TC-STZQDD
parent: REQ-XGWSK2K
order: aX
links:
  - type: verifies
    target: REQ-KQ7SN5H
    confirmed: ecd7ff8ad13d
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
