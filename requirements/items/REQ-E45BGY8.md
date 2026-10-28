---
id: TC-KG8Z7C
type: test-case
title: "Verify: Regulation loop measures the room temperature"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - connectivity
  - release-2.0
parent: INFO-MS9DAG
order: 180
links:
  - type: verifies
    target: SYS-RE1KVT
    confirmed: 33051d32765f
  - type: verifies
    target: SW-2TBDPG
    confirmed: a13f7b1862ac
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
