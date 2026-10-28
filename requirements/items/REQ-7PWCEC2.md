---
id: REQ-7PWCEC2
type: test-case
title: "Verify: Relay board restores relay events"
status: Approved
owner: A. Hassan
former-id: TC-1TZSTX
parent: REQ-F9Z1FYS
order: b0d
links:
  - type: verifies
    target: REQ-2QERQ97
    confirmed: a37e51579246
  - type: verifies
    target: REQ-QBK4Z02
    confirmed: a23609dd7210
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
