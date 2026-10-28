---
id: TC-TK4F9V
type: test-case
title: "Verify: Over-temperature monitor stores audit records"
status: Draft
owner: J. Müller
tags:
  - regulatory
  - cost
parent: INFO-Z4TW4B
order: 580
links:
  - type: verifies
    target: SYS-WQRW57
    confirmed: a077b95b29b8
  - type: verifies
    target: SW-0B9G6V
    confirmed: 4dd853c054a2
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
