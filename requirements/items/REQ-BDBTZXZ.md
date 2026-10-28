---
id: REQ-BDBTZXZ
type: test-case
title: "Verify: Device registry validates firmware images"
status: Approved
owner: N. Kamal
tags:
  - safety
  - release-1.0
former-id: TC-G68ZBQ
parent: REQ-8351896
order: b1W
links:
  - type: verifies
    target: REQ-HH7JK9T
    confirmed: 83294ed50340
  - type: verifies
    target: REQ-FDD7KZG
    confirmed: 74bdaa9f6306
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
