---
id: REQ-517HYHE
type: test-case
title: "Regression: Schedule editor switchs the room temperature"
status: Approved
owner: J. Müller
former-id: TC-5F9SHZ
parent: REQ-6H15AV2
order: b1L
links:
  - type: verifies
    target: REQ-Z94YSEP
    confirmed: 7c18672779dd
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
