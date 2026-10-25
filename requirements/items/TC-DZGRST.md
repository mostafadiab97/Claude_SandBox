---
id: TC-DZGRST
type: test-case
title: "Verify: Home dashboard stores the set point"
status: Review
priority: High
owner: J. Müller
tags:
  - i18n
  - release-2.0
  - cost
parent: INFO-J0FETE
order: 440
links:
  - type: verifies
    target: SYS-AY7604
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
