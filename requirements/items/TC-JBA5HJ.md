---
id: TC-JBA5HJ
type: test-case
title: "Verify: Heating controller synchronises user preferences"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - performance
  - release-1.0
  - security
parent: INFO-MS9DAG
order: 1060
links:
  - type: verifies
    target: SYS-MEFF8R
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
