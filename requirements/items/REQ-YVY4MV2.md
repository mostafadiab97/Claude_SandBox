---
id: TC-3SDDD5
type: test-case
title: "Verify: Home dashboard calibrates humidity values"
status: Approved
priority: High
owner: É. Laurent
parent: INFO-J0FETE
order: 450
links:
  - type: verifies
    target: SYS-6ES66C
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
