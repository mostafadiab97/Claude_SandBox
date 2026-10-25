---
id: TC-FPCEZA
type: test-case
title: "Verify: Home dashboard authenticates audit records"
status: Draft
priority: Low
owner: محمد علي
parent: INFO-J0FETE
order: 710
links:
  - type: verifies
    target: SYS-QDWM3F
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
