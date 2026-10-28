---
id: REQ-FF836HK
type: test-case
title: "Regression: Watchdog logs the connection state"
status: Review
priority: Medium
owner: L. Samir
former-id: TC-8X947E
parent: REQ-6H15AV2
order: b0S
links:
  - type: verifies
    target: REQ-W18RFR4
    confirmed: 2d379fb34255
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
