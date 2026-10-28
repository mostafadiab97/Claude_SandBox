---
id: REQ-F4HD24T
type: test-case
title: "Regression: Home dashboard restores user preferences"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-DXNCAK
parent: REQ-6H15AV2
order: b2H
links:
  - type: verifies
    target: REQ-YW090BX
    confirmed: 5727fec8b08d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
