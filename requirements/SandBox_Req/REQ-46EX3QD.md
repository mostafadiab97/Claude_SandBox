---
id: REQ-46EX3QD
type: test-case
title: "Regression: OTA server measures energy consumption"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
former-id: TC-M5QBZ2
parent: REQ-6H15AV2
order: b0v
links:
  - type: verifies
    target: REQ-QFMXM3D
    confirmed: 69daa9458ae7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
