---
id: REQ-DCPG729
type: test-case
title: "Verify: Zone valve detects access tokens"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - accessibility
  - release-1.0
former-id: TC-AQCVKV
parent: REQ-XGWSK2K
order: b17
links:
  - type: verifies
    target: REQ-PYT0J5S
    confirmed: 36689a624b77
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
