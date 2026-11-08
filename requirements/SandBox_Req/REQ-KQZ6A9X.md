---
id: REQ-KQZ6A9X
type: test-case
title: "Verify: Bluetooth LE link switchs the room temperature"
status: Obsolete
owner: A. Hassan
tags:
  - customer-request
former-id: TC-N229CR
parent: REQ-67RQXCK
order: aH
links:
  - type: verifies
    target: REQ-XED1QNH
    confirmed: 400a2ed062a9
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
