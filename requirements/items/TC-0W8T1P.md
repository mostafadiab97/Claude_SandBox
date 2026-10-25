---
id: TC-0W8T1P
type: test-case
title: "Verify: Regulation loop notifys firmware images"
status: Approved
priority: High
owner: S. Adel
tags:
  - power
parent: INFO-MS9DAG
order: 860
links:
  - type: verifies
    target: SYS-Q6QXAC
    confirmed: e67f8d759f40
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
