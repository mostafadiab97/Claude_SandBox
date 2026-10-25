---
id: TC-DXG9A2
type: test-case
title: "Verify: Cloud backend detects the set point"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
parent: INFO-7P4D8D
order: 1080
links:
  - type: verifies
    target: SYS-7560Q0
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
