---
id: TC-PSEKH5
type: test-case
title: "Verify: Regulation loop stores audit records"
status: Obsolete
priority: High
owner: S. Adel
parent: INFO-MS9DAG
order: 1230
links:
  - type: verifies
    target: SYS-5449PV
  - type: verifies
    target: SW-TH8P9M
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
