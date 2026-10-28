---
id: TC-WB4CDM
type: test-case
title: "Verify: Heating controller limits the room temperature"
status: Draft
owner: M. Farouk
parent: INFO-MS9DAG
order: 290
links:
  - type: verifies
    target: SYS-A6Z44C
    confirmed: f442eb9491f7
  - type: verifies
    target: SW-MV99XM
    confirmed: ebb6a7b1b83a
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
