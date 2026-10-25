---
id: TC-TPDENB
type: test-case
title: "Verify: User account service restores schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - power
parent: INFO-7P4D8D
order: 1590
links:
  - type: verifies
    target: SYS-2NJC1D
  - type: verifies
    target: SW-1DHCGS
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
