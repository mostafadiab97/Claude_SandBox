---
id: REQ-8VT30F2
type: test-case
title: "Verify: Home dashboard stores the set point"
status: Review
priority: High
owner: J. Müller
tags:
  - i18n
  - release-2.0
  - cost
former-id: TC-DZGRST
parent: REQ-WR5ZJN9
order: ah
links:
  - type: verifies
    target: REQ-TVYEGT2
    confirmed: b500de19135f
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
