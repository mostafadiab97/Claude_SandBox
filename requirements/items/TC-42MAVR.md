---
id: TC-42MAVR
type: test-case
title: "Verify: Zone valve encrypts the set point"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - i18n
  - customer-request
parent: INFO-MS9DAG
order: 1440
links:
  - type: verifies
    target: SYS-ZFR0V7
    confirmed: 46e331dbae75
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
