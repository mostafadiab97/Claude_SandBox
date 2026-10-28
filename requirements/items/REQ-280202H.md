---
id: TC-EF7MWB
type: test-case
title: "Verify: Relay board authenticates the set point"
status: Review
priority: Medium
owner: S. Adel
tags:
  - customer-request
  - regulatory
parent: INFO-MACGC3
order: 1080
links:
  - type: verifies
    target: SYS-61BADB
    confirmed: 8aabb6fc11d2
  - type: verifies
    target: SW-DP9XAE
    confirmed: de0e79bdb5ad
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
