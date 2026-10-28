---
id: TC-MD17NH
type: test-case
title: "Verify: Boiler interface measures the room temperature"
status: Approved
priority: High
owner: S. Adel
tags:
  - regulatory
  - ux
  - customer-request
parent: INFO-MS9DAG
order: 850
links:
  - type: verifies
    target: SYS-WX9A1X
    confirmed: c84f4efc6cd4
  - type: verifies
    target: SW-0WEH9P
    confirmed: 9d0e0ac81929
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
