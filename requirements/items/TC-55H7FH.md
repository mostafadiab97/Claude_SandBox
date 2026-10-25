---
id: TC-55H7FH
type: test-case
title: "Verify: Heating controller synchronises safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-1.0
  - performance
  - customer-request
parent: INFO-MS9DAG
order: 20
links:
  - type: verifies
    target: SYS-338WGX
    confirmed: ba9b4f21444e
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
