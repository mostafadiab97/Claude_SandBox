---
id: REQ-2H16FGD
type: test-case
title: "Verify: Bluetooth LE link synchronises relay events"
status: Approved
priority: Low
owner: J. Müller
former-id: TC-YHGJWN
parent: REQ-67RQXCK
order: b0k
links:
  - type: verifies
    target: REQ-07KDR3K
    confirmed: edacad3b5f35
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
