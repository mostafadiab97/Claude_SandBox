---
id: TC-VRSJ7Y
type: test-case
title: "Verify: Heat pump driver synchronises user preferences"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
  - regulatory
parent: INFO-MS9DAG
order: 370
links:
  - type: verifies
    target: SYS-GECB0Q
  - type: verifies
    target: SW-MGBSAX
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
