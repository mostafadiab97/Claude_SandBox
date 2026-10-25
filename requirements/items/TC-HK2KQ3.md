---
id: TC-HK2KQ3
type: test-case
title: "Verify: Heat pump driver stores the operating mode"
status: Draft
priority: High
owner: R. Nabil
tags:
  - accessibility
  - i18n
  - ux
parent: INFO-MS9DAG
order: 120
links:
  - type: verifies
    target: SYS-JFB5KX
    confirmed: 270d776a5c32
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
