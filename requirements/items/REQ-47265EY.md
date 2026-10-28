---
id: TC-1NCSGG
type: test-case
title: "Verify: Zone valve reports firmware images"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - security
parent: INFO-MS9DAG
order: 160
links:
  - type: verifies
    target: SYS-SK1ZFN
    confirmed: 65625f74ff05
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
