---
id: TC-CHSNPW
type: test-case
title: "Verify: Heating controller calibrates audit records"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - customer-request
  - release-2.0
parent: INFO-MS9DAG
order: 380
links:
  - type: verifies
    target: SYS-KS8K75
    confirmed: 6713f81a0fb0
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
