---
id: TC-7XJ6DA
type: test-case
title: "Verify: Battery backup validates the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - power
parent: INFO-MACGC3
order: 890
links:
  - type: verifies
    target: SYS-V3KNC0
    confirmed: c71efbcdb7bc
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
