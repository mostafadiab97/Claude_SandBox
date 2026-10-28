---
id: REQ-TMANZB1
type: test-case
title: "Verify: Bluetooth LE link detects user preferences"
status: Approved
priority: Medium
owner: A. Hassan
former-id: TC-6RW9BP
parent: REQ-67RQXCK
order: b0Z
links:
  - type: verifies
    target: REQ-0N3YVR9
    confirmed: 7c651b78b359
  - type: verifies
    target: REQ-JY483TG
    confirmed: 26fa635a4e70
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
