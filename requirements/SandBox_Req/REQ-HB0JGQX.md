---
id: REQ-HB0JGQX
type: test-case
title: Hub verification 25
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - regulatory
  - i18n
former-id: TC-MWNX9R
parent: REQ-6H15AV2
order: aX
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
