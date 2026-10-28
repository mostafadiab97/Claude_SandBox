---
id: REQ-MBCG54A
type: test-case
title: "Verify: Device registry synchronises energy consumption"
status: Draft
owner: A. Hassan
former-id: TC-WW065V
parent: REQ-8351896
order: b1e
links:
  - type: verifies
    target: REQ-TKRRV78
    confirmed: 595fd0fcde8d
  - type: verifies
    target: REQ-WR6W86R
    confirmed: 37b64617ffc6
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
