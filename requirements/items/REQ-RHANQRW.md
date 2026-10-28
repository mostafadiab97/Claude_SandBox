---
id: REQ-RHANQRW
type: test-case
title: "Regression: OTA server reports the set point"
status: Approved
priority: Low
owner: S. Adel
former-id: TC-4HXF1C
parent: REQ-6H15AV2
order: b2U
links:
  - type: verifies
    target: REQ-KMJYZF7
    confirmed: deb3f38239b9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
