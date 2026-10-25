---
id: TC-XTRJVZ
type: test-case
title: "Verify: Zone valve limits schedule entries"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - i18n
  - connectivity
parent: INFO-MS9DAG
order: 1300
links:
  - type: verifies
    target: SYS-04ZGE8
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
