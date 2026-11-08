---
id: REQ-GSNSVTB
type: test-case
title: "Regression: Touch display notifys the room temperature"
status: Approved
owner: Y. Saber
former-id: TC-N5JKHW
parent: REQ-6H15AV2
order: b1o
links:
  - type: verifies
    target: REQ-YG8BZ77
    confirmed: 631388ab0b1c
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
