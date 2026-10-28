---
id: REQ-9JW6VJ9
type: test-case
title: "Regression: Login screen notifys the room temperature"
status: Obsolete
former-id: TC-3HSDD7
parent: REQ-6H15AV2
order: b2A
links:
  - type: verifies
    target: REQ-4GW7FRK
    confirmed: 77747505e6c0
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
