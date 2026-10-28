---
id: REQ-MVHE821
type: test-case
title: "Regression: Power supply measures sensor readings"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - connectivity
  - EMC
former-id: TC-N12THW
parent: REQ-6H15AV2
order: b2R
links:
  - type: verifies
    target: REQ-TVXQNBY
    confirmed: a81e8767fb91
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
