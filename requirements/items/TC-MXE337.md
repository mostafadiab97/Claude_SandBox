---
id: TC-MXE337
type: test-case
title: "Verify: Login screen notifys firmware images"
status: Review
priority: Medium
owner: É. Laurent
parent: INFO-J0FETE
order: 840
links:
  - type: verifies
    target: SYS-PERCNX
  - type: verifies
    target: SW-G6TGXX
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
