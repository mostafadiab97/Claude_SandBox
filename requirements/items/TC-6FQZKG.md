---
id: TC-6FQZKG
type: test-case
title: "Verify: Heat pump driver authenticates energy consumption"
status: Draft
owner: N. Kamal
tags:
  - cost
  - performance
parent: INFO-MS9DAG
order: 710
links:
  - type: verifies
    target: SYS-64T5WP
  - type: verifies
    target: SW-CQC35W
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
