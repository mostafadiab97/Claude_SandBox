---
id: REQ-0GRVVME
type: test-case
title: "Verify: Heat pump driver synchronises energy consumption"
status: Approved
owner: K. Tanaka
tags:
  - connectivity
  - safety
former-id: TC-DPJ856
parent: REQ-XGWSK2K
order: ag
links:
  - type: verifies
    target: REQ-DWD5W03
    confirmed: 8050d4028450
  - type: verifies
    target: REQ-J10GYGS
    confirmed: 914d7cae9637
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
