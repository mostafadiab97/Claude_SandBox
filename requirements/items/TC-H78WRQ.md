---
id: TC-H78WRQ
type: test-case
title: "Verify: Schedule editor calibrates audit records"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - connectivity
  - security
  - cost
parent: INFO-J0FETE
order: 1050
links:
  - type: verifies
    target: SYS-WZPXT3
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
