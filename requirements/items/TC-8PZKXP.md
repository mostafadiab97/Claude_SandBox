---
id: TC-8PZKXP
type: test-case
title: "Verify: Heating controller reports the operating mode"
status: Draft
priority: Low
owner: A. Hassan
parent: INFO-MS9DAG
order: 500
links:
  - type: verifies
    target: SYS-WNF4KZ
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
