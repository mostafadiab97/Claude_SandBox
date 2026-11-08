---
id: REQ-73X35WJ
type: test-case
title: "Regression: Main PCB measures firmware images"
status: Draft
priority: Low
owner: M. Farouk
former-id: TC-2RZ6M5
parent: REQ-6H15AV2
order: b1J
links:
  - type: verifies
    target: REQ-8WGXNDY
    confirmed: 95a8578d9835
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
