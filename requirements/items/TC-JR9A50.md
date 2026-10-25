---
id: TC-JR9A50
type: test-case
title: "Verify: Heating controller measures user preferences"
status: Review
owner: R. Nabil
tags:
  - customer-request
  - cost
parent: INFO-MS9DAG
order: 1310
links:
  - type: verifies
    target: SYS-YC69H2
  - type: verifies
    target: SW-N3NVXW
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
