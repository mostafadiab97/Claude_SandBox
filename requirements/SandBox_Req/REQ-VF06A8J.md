---
id: REQ-VF06A8J
type: test-case
title: "Verify: Menu system measures firmware images"
status: Approved
priority: Medium
owner: S. Adel
former-id: TC-4E721R
parent: REQ-Y9VHHKA
order: b1B
links:
  - type: verifies
    target: REQ-XWFNNXT
    confirmed: a080ef16fc5e
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
