---
id: TC-AD54Z2
type: test-case
title: "Verify: Home dashboard synchronises schedule entries"
status: Review
priority: Low
owner: N. Kamal
parent: INFO-J0FETE
order: 970
links:
  - type: verifies
    target: SYS-QBP134
  - type: verifies
    target: SW-RKA76Z
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
