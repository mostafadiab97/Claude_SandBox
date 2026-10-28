---
id: TC-PSPCG1
type: test-case
title: "Verify: Heating controller encrypts user preferences"
status: Obsolete
priority: Medium
owner: H. Mostafa
parent: INFO-MS9DAG
order: 320
links:
  - type: verifies
    target: SYS-4JQMJS
    confirmed: 5acdb7574d9f
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Validate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
