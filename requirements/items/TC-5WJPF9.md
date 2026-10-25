---
id: TC-5WJPF9
type: test-case
title: "Verify: Boiler interface limits the set point"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - safety
  - i18n
parent: INFO-MS9DAG
order: 970
links:
  - type: verifies
    target: SYS-KVWKZF
    confirmed: 9148889bdd96
  - type: verifies
    target: SW-0B9G6V
    confirmed: 4dd853c054a2
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
