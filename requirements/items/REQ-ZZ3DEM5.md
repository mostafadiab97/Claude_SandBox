---
id: REQ-ZZ3DEM5
type: test-case
title: "Regression: Enclosure calibrates firmware images"
status: Draft
owner: É. Laurent
former-id: TC-41M1Z7
parent: REQ-6H15AV2
order: b1Y
links:
  - type: verifies
    target: REQ-79Q9433
    confirmed: fcf4c01f1afd
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
