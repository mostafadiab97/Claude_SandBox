---
id: REQ-NRB153D
type: test-case
title: "Regression: Notification service validates humidity values"
status: Obsolete
priority: Medium
owner: H. Mostafa
tags:
  - ux
former-id: TC-4EFH7M
parent: REQ-6H15AV2
order: b0Z
links:
  - type: verifies
    target: REQ-AN2GRAB
    confirmed: 0f09ad7fec21
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
