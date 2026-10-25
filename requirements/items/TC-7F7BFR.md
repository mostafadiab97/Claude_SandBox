---
id: TC-7F7BFR
type: test-case
title: "Verify: OTA server stores user preferences"
status: Draft
priority: High
owner: L. Samir
tags:
  - cost
  - release-2.0
parent: INFO-7P4D8D
order: 1200
links:
  - type: verifies
    target: SYS-0AQ1WN
  - type: verifies
    target: SW-9EEFDN
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
