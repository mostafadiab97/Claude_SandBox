---
id: TC-C80ADT
type: test-case
title: "Verify: Regulation loop authenticates access tokens"
status: Obsolete
priority: Medium
owner: Y. Saber
parent: INFO-MS9DAG
order: 630
links:
  - type: verifies
    target: SYS-GCSJ6X
    confirmed: bc98a50160a3
  - type: verifies
    target: SW-MGBSAX
    confirmed: bb0b38fdb7a5
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
