---
id: TC-7MEGMB
type: test-case
title: "Verify: Regulation loop notifys the room temperature"
status: Draft
priority: High
owner: L. Samir
tags:
  - security
parent: INFO-MS9DAG
order: 1490
links:
  - type: verifies
    target: SYS-1DTP29
  - type: verifies
    target: SW-75XXSR
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
