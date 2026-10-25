---
id: TC-7KGKSB
type: test-case
title: "Verify: Boiler interface logs user preferences"
status: Draft
priority: High
owner: N. Kamal
tags:
  - EMC
  - release-2.0
  - release-1.0
parent: INFO-MS9DAG
order: 880
links:
  - type: verifies
    target: SYS-6SJ3GD
  - type: verifies
    target: SW-SHA6RD
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
