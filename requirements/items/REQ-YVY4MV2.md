---
id: REQ-YVY4MV2
type: test-case
title: "Verify: Home dashboard calibrates humidity values"
status: Approved
priority: High
owner: É. Laurent
former-id: TC-3SDDD5
parent: REQ-WR5ZJN9
order: ai
links:
  - type: verifies
    target: REQ-3J5F3Z3
    confirmed: ec8cd1bbb3ad
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
