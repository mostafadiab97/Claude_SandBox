---
id: TC-Z3VV6X
type: test-case
title: "Verify: Heat pump driver restores error conditions"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-MS9DAG
order: 470
links:
  - type: verifies
    target: SYS-XSDXN6
  - type: verifies
    target: SW-R9KVRR
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
