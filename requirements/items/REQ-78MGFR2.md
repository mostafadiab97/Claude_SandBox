---
id: TC-MHSX1M
type: test-case
title: "Verify: Regulation loop switchs the operating mode"
status: Review
priority: High
owner: محمد علي
tags:
  - release-2.0
  - ux
parent: INFO-MS9DAG
order: 990
links:
  - type: verifies
    target: SYS-C1KANF
    confirmed: c1311b4a3390
  - type: verifies
    target: SW-KBQ6EC
    confirmed: 1aed1bac3759
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
