---
id: REQ-1J312VE
type: test-case
title: "Regression: Touch display notifys firmware images"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - i18n
  - connectivity
former-id: TC-MAETV5
parent: REQ-6H15AV2
order: az
links:
  - type: verifies
    target: REQ-N13Q3PD
    confirmed: 3214f1c9f970
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
