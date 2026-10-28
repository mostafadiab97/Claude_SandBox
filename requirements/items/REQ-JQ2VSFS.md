---
id: REQ-JQ2VSFS
type: test-case
title: Hub verification 6
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - regulatory
  - ux
  - i18n
former-id: TC-0YK2DC
parent: REQ-6H15AV2
order: aE
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
