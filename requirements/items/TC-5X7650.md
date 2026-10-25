---
id: TC-5X7650
type: test-case
title: "Verify: Zone valve notifys schedule entries"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - i18n
parent: INFO-MS9DAG
order: 530
links:
  - type: verifies
    target: SYS-MSJYD9
    confirmed: a4f989d37c98
  - type: verifies
    target: SW-NWQESS
    confirmed: 02be29037617
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
