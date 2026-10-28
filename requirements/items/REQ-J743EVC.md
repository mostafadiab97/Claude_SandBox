---
id: TC-QGG4X6
type: test-case
title: "Verify: Boiler interface logs firmware images"
status: Review
priority: High
owner: A. Hassan
tags:
  - cost
  - release-1.0
  - accessibility
parent: INFO-MS9DAG
order: 520
links:
  - type: verifies
    target: SYS-CE57ME
    confirmed: 4e23886933b6
  - type: verifies
    target: SW-NWS6XP
    confirmed: 5f492f9366b1
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
