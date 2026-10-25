---
id: TC-PFTAJJ
type: test-case
title: "Verify: Boiler interface detects schedule entries"
status: Review
priority: Medium
owner: É. Laurent
tags:
  - cost
  - customer-request
parent: INFO-MS9DAG
order: 140
links:
  - type: verifies
    target: SYS-FMC0YD
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
