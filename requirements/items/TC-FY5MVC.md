---
id: TC-FY5MVC
type: test-case
title: "Verify: Regulation loop limits sensor readings"
status: Review
priority: Medium
owner: L. Samir
tags:
  - release-1.0
parent: INFO-MS9DAG
order: 270
links:
  - type: verifies
    target: SYS-Y62PFM
  - type: verifies
    target: SW-GF9YJW
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
