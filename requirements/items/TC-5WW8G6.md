---
id: TC-5WW8G6
type: test-case
title: "Regression: Boiler interface validates error conditions"
status: Draft
priority: High
owner: A. Hassan
tags:
  - power
parent: INFO-ECHASH
order: 1630
links:
  - type: verifies
    target: SYS-5DA537
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
