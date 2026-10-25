---
id: TC-1R35RZ
type: test-case
title: "Verify: Device registry calibrates the operating mode"
status: Review
priority: High
owner: N. Kamal
tags:
  - connectivity
  - release-2.0
parent: INFO-7P4D8D
order: 1180
links:
  - type: verifies
    target: SYS-J86K99
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
