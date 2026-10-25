---
id: TC-NMR3WN
type: test-case
title: "Verify: Encryption layer switchs the room temperature"
status: Obsolete
priority: High
owner: É. Laurent
tags:
  - EMC
  - security
parent: INFO-Z4TW4B
order: 820
links:
  - type: verifies
    target: SYS-BBX6H4
  - type: verifies
    target: SW-95QS75
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
