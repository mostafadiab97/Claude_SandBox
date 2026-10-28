---
id: REQ-GJ775BZ
type: test-case
title: "Verify: Bluetooth LE link synchronises schedule entries"
status: Approved
priority: Medium
owner: A. Hassan
former-id: TC-CPP7BR
parent: REQ-67RQXCK
order: aG
links:
  - type: verifies
    target: REQ-Q1BR7H4
    confirmed: e4a2c3843dd6
  - type: verifies
    target: REQ-DAD6G4W
    confirmed: 50a966ab45a5
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
