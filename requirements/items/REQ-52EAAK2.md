---
id: TC-1PSEH6
type: test-case
title: "Verify: Cloud backend stores the set point"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - safety
  - EMC
parent: INFO-7P4D8D
order: 1360
links:
  - type: verifies
    target: SYS-E22H2H
    confirmed: ee4438e7f317
  - type: verifies
    target: SW-YDB75D
    confirmed: 63cf0f5701dc
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Notify user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
