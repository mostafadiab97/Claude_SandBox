---
id: TC-MVY50N
type: test-case
title: "Verify: OTA server synchronises sensor readings"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
  - safety
parent: INFO-7P4D8D
order: 990
links:
  - type: verifies
    target: SYS-RBD8MR
    confirmed: fce90764ac1a
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
