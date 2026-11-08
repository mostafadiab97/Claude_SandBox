---
id: REQ-63QT60Q
type: test-case
title: Hub verification 20
status: Draft
priority: High
owner: A. Hassan
tags:
  - customer-request
former-id: TC-KGK67Q
parent: REQ-6H15AV2
order: aS
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
