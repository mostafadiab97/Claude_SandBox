---
id: TC-9HYWQH
type: test-case
title: "Verify: Regulation loop calibrates firmware images"
status: Draft
owner: É. Laurent
tags:
  - release-2.0
  - connectivity
parent: INFO-MS9DAG
order: 540
links:
  - type: verifies
    target: SYS-XP4ZAH
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Display firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
