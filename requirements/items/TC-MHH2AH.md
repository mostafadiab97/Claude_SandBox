---
id: TC-MHH2AH
type: test-case
title: "Verify: Heating controller validates safety limits"
status: Review
owner: S. Adel
parent: INFO-MS9DAG
order: 10
links:
  - type: verifies
    target: SYS-GWH086
  - type: verifies
    target: SW-2WMVD4
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
