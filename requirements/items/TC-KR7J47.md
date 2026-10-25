---
id: TC-KR7J47
type: test-case
title: "Verify: Home dashboard calibrates audit records"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - connectivity
  - regulatory
  - ux
parent: INFO-J0FETE
order: 1520
links:
  - type: verifies
    target: SYS-6085Y8
  - type: verifies
    target: SW-8EV7YV
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
