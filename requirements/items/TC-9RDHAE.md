---
id: TC-9RDHAE
type: test-case
title: "Verify: Pairing process authenticates the set point"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-2.0
  - connectivity
  - cost
parent: INFO-F0M7VC
order: 70
links:
  - type: verifies
    target: SYS-DZWWWA
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
