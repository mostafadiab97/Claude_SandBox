---
id: REQ-AY8ADVS
type: test-case
title: "Regression: Wi-Fi module authenticates the room temperature"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-X8ZH2Y
parent: REQ-6H15AV2
order: b1u
links:
  - type: verifies
    target: REQ-GHJK43J
    confirmed: a8274ea6218e
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
