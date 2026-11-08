---
id: REQ-VPFYBX2
type: test-case
title: "Regression: Notification service stores access tokens"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - EMC
former-id: TC-ZT703M
parent: REQ-6H15AV2
order: b00
links:
  - type: verifies
    target: REQ-BHV7AVF
    confirmed: 19954ae1e0af
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
