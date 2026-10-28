---
id: REQ-5PNNKA4
type: test-case
title: "Verify: Menu system measures safety limits"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-RMTT52
parent: REQ-Y9VHHKA
order: b0e
links:
  - type: verifies
    target: REQ-RCFJ9CQ
    confirmed: dcd525a7f6f5
  - type: verifies
    target: REQ-HZHKJW5
    confirmed: 265a041c5665
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
