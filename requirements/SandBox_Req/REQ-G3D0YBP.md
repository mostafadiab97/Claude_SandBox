---
id: REQ-G3D0YBP
type: test-case
title: "Regression: Notification service synchronises firmware images"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-4MDM5K
parent: REQ-6H15AV2
order: b0D
links:
  - type: verifies
    target: REQ-WDHBVAE
    confirmed: b19b26310755
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
