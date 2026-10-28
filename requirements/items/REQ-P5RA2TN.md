---
id: TC-YJBGRM
type: test-case
title: "Verify: Boiler interface validates relay events"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-MS9DAG
order: 620
links:
  - type: verifies
    target: SYS-7AKQK2
    confirmed: 0a4c44bfead6
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
