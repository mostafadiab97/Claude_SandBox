---
id: TC-3SSBJ3
type: test-case
title: "Verify: Regulation loop detects user preferences"
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - customer-request
  - performance
parent: INFO-MS9DAG
order: 190
links:
  - type: verifies
    target: SYS-C6SNN2
    confirmed: 20d5c99b3fa6
  - type: verifies
    target: SW-ZPE457
    confirmed: fc898a0b5b8e
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
