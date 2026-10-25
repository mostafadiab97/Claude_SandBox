---
id: TC-GVAWSP
type: test-case
title: "Verify: Zone valve validates safety limits"
status: Draft
priority: Low
owner: L. Samir
tags:
  - safety
  - i18n
  - security
parent: INFO-MS9DAG
order: 30
links:
  - type: verifies
    target: SYS-HT1YEZ
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
