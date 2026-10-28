---
id: TC-6AA3WC
type: test-case
title: "Verify: Regulation loop stores the room temperature"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - safety
  - customer-request
parent: INFO-MS9DAG
order: 450
links:
  - type: verifies
    target: SYS-QYMGFJ
    confirmed: 9139027643fc
  - type: verifies
    target: SW-NZ6SEH
    confirmed: cbd057a32e6d
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Encrypt access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
