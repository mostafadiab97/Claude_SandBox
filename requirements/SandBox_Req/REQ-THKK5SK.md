---
id: REQ-THKK5SK
type: test-case
title: "Verify: Schedule editor stores firmware images"
status: Approved
owner: K. Tanaka
former-id: TC-7209XR
parent: REQ-WR5ZJN9
order: b15
links:
  - type: verifies
    target: REQ-XBE1312
    confirmed: 1293558404d1
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
