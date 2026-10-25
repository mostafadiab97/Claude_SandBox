---
id: TC-Y9DJ1B
type: test-case
title: "Verify: Zone valve measures relay events"
status: Approved
priority: High
owner: Y. Saber
tags:
  - i18n
parent: INFO-MS9DAG
order: 1280
links:
  - type: verifies
    target: SYS-K8NQFV
  - type: verifies
    target: SW-DN2SKS
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
