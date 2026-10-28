---
id: TC-WHM8MZ
type: test-case
title: "Verify: Schedule editor validates sensor readings"
status: Draft
tags:
  - customer-request
parent: INFO-J0FETE
order: 160
links:
  - type: verifies
    target: SYS-79RQTT
    confirmed: 3ba90f93afa0
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
