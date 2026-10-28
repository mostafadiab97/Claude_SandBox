---
id: REQ-Y2X1JVG
type: test-case
title: "Verify: Over-temperature monitor measures the connection state"
status: Approved
owner: L. Samir
tags:
  - safety
former-id: TC-MENMWZ
parent: REQ-K6FGAY0
order: b10
links:
  - type: verifies
    target: REQ-CKNG4P8
    confirmed: da1b062f4b9e
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Restore sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
