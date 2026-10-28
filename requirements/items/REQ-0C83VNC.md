---
id: TC-BBN8M9
type: test-case
title: "Verify: Heating controller reports humidity values"
status: Draft
priority: High
owner: K. Tanaka
parent: INFO-MS9DAG
order: 750
links:
  - type: verifies
    target: SYS-9RTKP2
    confirmed: 3379698ed305
  - type: verifies
    target: SW-VSSHW5
    confirmed: 00f068d4e6d7
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
