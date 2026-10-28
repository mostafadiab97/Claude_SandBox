---
id: REQ-JJDSY2M
type: test-case
title: "Regression: Heat pump driver notifys humidity values"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - EMC
former-id: TC-53WT3P
parent: REQ-6H15AV2
order: b2F
links:
  - type: verifies
    target: REQ-CFE22NG
    confirmed: f2f1228e62f7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
