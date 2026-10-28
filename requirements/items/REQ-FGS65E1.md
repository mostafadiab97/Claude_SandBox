---
id: TC-3FMF11
type: test-case
title: "Verify: Battery backup calibrates humidity values"
status: Approved
priority: High
owner: É. Laurent
parent: INFO-MACGC3
order: 430
links:
  - type: verifies
    target: SYS-324HGW
    confirmed: 827d08f24199
  - type: verifies
    target: SW-FFZVBX
    confirmed: ecef233cdc2e
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
