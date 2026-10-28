---
id: REQ-V0ZYATH
type: test-case
title: "Regression: Mobile app authenticates safety limits"
status: Approved
priority: High
owner: A. Hassan
former-id: TC-ZGE6VD
parent: REQ-6H15AV2
order: b21
links:
  - type: verifies
    target: REQ-DQBXXZR
    confirmed: e29ae9264b3a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
