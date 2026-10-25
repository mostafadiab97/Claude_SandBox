---
id: TC-TAQ8E2
type: test-case
title: "Verify: Mobile app logs audit records"
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-J0FETE
order: 1180
links:
  - type: verifies
    target: SYS-RZKYW5
  - type: verifies
    target: SW-R2ANQB
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
