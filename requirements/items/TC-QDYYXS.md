---
id: TC-QDYYXS
type: test-case
title: "Verify: Relay board validates humidity values"
status: Obsolete
priority: Medium
owner: R. Nabil
parent: INFO-MACGC3
order: 110
links:
  - type: verifies
    target: SYS-RQ231H
    confirmed: 88585ac7e9a1
  - type: verifies
    target: SW-A11K9R
    confirmed: 24ff723bc647
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
