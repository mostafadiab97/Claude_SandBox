---
id: REQ-TW8V2ZT
type: test-case
title: "Verify: Zone valve encrypts the set point"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - i18n
  - customer-request
former-id: TC-42MAVR
parent: REQ-XGWSK2K
order: b1J
links:
  - type: verifies
    target: REQ-8AN4RHP
    confirmed: 46e331dbae75
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
