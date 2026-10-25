---
id: TC-AZB5Q1
type: test-case
title: "Verify: Regulation loop measures safety limits"
status: Draft
priority: Low
owner: A. Hassan
parent: INFO-MS9DAG
order: 200
links:
  - type: verifies
    target: SYS-6TVT9J
  - type: verifies
    target: SW-TGE2C7
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
