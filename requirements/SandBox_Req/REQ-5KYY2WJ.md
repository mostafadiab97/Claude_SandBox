---
id: REQ-5KYY2WJ
type: test-case
title: "Verify: Bluetooth LE link reports the room temperature"
status: Review
priority: Low
owner: محمد علي
former-id: TC-SXVMX3
parent: REQ-67RQXCK
order: aI
links:
  - type: verifies
    target: REQ-D0AFD98
    confirmed: f32411f63461
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Log energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
