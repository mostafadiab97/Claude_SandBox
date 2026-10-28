---
id: REQ-9BFHXTY
type: test-case
title: "Verify: Menu system authenticates safety limits"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-ZB1J97
parent: REQ-Y9VHHKA
order: b07
links:
  - type: verifies
    target: REQ-RE2TJFJ
    confirmed: 87ab2e4b1288
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
