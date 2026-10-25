---
id: TC-11PDTM
type: test-case
title: "Verify: Home dashboard logs safety limits"
status: Approved
priority: High
owner: L. Samir
parent: INFO-J0FETE
order: 1310
links:
  - type: verifies
    target: SYS-BGBCA1
    confirmed: 9336011838ef
  - type: verifies
    target: SW-YZSBP4
    confirmed: 77cb9f1654aa
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
