---
id: REQ-T3DS8TH
type: test-case
title: "Verify: Enclosure limits safety limits"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - release-1.0
former-id: TC-NWK8JY
parent: REQ-F9Z1FYS
order: at
links:
  - type: verifies
    target: REQ-ERXSPD6
    confirmed: 4221a4e34c0d
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
