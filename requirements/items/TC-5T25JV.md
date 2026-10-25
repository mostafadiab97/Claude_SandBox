---
id: TC-5T25JV
type: test-case
title: "Verify: Heating controller displays the connection state"
status: Draft
priority: High
tags:
  - accessibility
  - customer-request
  - performance
parent: INFO-MS9DAG
order: 400
links:
  - type: verifies
    target: SYS-F5RTF4
    confirmed: 72eb3d42eaa8
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
