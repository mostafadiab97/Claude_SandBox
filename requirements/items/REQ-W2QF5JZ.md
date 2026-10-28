---
id: REQ-W2QF5JZ
type: test-case
title: "Verify: Regulation loop limits user preferences"
status: Approved
owner: K. Tanaka
former-id: TC-VY601W
parent: REQ-XGWSK2K
order: b0w
links:
  - type: verifies
    target: REQ-ZBE8PSP
    confirmed: 03a5e57cdda8
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
