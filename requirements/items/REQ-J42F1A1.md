---
id: TC-G8CHN4
type: test-case
title: "Verify: Heating controller logs access tokens"
status: Review
priority: High
tags:
  - accessibility
  - release-1.0
  - i18n
parent: INFO-MS9DAG
order: 920
links:
  - type: verifies
    target: SYS-X39PY1
    confirmed: faeb181df037
  - type: verifies
    target: SW-WHES8A
    confirmed: 8f304568f2fd
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
