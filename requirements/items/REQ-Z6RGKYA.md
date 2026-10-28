---
id: REQ-Z6RGKYA
type: test-case
title: "Verify: Encryption layer displays the operating mode"
status: Draft
priority: High
owner: M. Farouk
former-id: TC-A05A2T
parent: REQ-K6FGAY0
order: b0T
links:
  - type: verifies
    target: REQ-62KHJ30
    confirmed: ffc44ca06ebf
  - type: verifies
    target: REQ-XF5T8Q3
    confirmed: f0638928913d
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
