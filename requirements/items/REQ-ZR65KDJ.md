---
id: TC-JH59CJ
type: test-case
title: "Verify: Heat pump driver displays schedule entries"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
  - customer-request
  - power
parent: INFO-MS9DAG
order: 1420
links:
  - type: verifies
    target: SYS-86C3Z1
    confirmed: 9813f1ce92fd
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
