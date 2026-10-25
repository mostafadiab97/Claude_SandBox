---
id: TC-J5DPB9
type: test-case
title: "Verify: Regulation loop synchronises audit records"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - regulatory
parent: INFO-MS9DAG
order: 1430
links:
  - type: verifies
    target: SYS-5FN1TB
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
