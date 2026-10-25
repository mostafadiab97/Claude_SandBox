---
id: TC-S28FDK
type: test-case
title: "Verify: User account service authenticates safety limits"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - cost
parent: INFO-7P4D8D
order: 1320
links:
  - type: verifies
    target: SYS-3CAV4T
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
