---
id: TC-MZFZBH
type: test-case
title: "Verify: Tamper detection notifys safety limits"
status: Approved
priority: Low
parent: INFO-Z4TW4B
order: 660
links:
  - type: verifies
    target: SYS-7DF4GN
    confirmed: b8942c9f4893
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
