---
id: TC-KZ8HAB
type: test-case
title: "Verify: Schedule editor detects the connection state"
status: Review
priority: Low
owner: A. Hassan
tags:
  - customer-request
  - power
  - security
parent: INFO-J0FETE
order: 1390
links:
  - type: verifies
    target: SYS-VRC80Y
    confirmed: 9e303efe85be
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
