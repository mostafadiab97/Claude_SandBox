---
id: TC-BK5DAM
type: test-case
title: "Verify: Regulation loop logs energy consumption"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
parent: INFO-MS9DAG
order: 720
links:
  - type: verifies
    target: SYS-G3EJDX
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
