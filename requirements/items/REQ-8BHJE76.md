---
id: TC-1N848H
type: test-case
title: "Verify: Pairing process measures audit records"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-F0M7VC
order: 850
links:
  - type: verifies
    target: SYS-XBES39
    confirmed: bc98487a5cdc
  - type: verifies
    target: SW-NGNJD8
    confirmed: 0210b675a2d9
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
