---
id: REQ-1N4TGD8
type: test-case
title: "Regression: Zone valve notifys the room temperature"
status: Obsolete
priority: Low
owner: R. Nabil
former-id: TC-75DS3K
parent: REQ-6H15AV2
order: at
links:
  - type: verifies
    target: REQ-VR7ZHR7
    confirmed: 93ee1defe30a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
