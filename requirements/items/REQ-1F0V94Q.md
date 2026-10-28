---
id: TC-Z1YDR4
type: test-case
title: "Verify: Schedule editor logs the connection state"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - ux
parent: INFO-J0FETE
order: 580
links:
  - type: verifies
    target: SYS-CSBXDS
    confirmed: 1344b9a930e1
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
