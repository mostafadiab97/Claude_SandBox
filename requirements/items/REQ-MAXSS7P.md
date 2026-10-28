---
id: REQ-MAXSS7P
type: test-case
title: "Verify: Menu system switchs humidity values"
status: Review
priority: Medium
former-id: TC-SX2GN8
parent: REQ-Y9VHHKA
order: b1K
links:
  - type: verifies
    target: REQ-0SY5BMS
    confirmed: 5df07efae901
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
