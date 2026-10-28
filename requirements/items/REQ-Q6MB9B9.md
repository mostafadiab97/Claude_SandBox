---
id: REQ-Q6MB9B9
type: test-case
title: Hub verification 30
status: Draft
priority: High
owner: S. Adel
tags:
  - customer-request
former-id: TC-6BZF52
parent: REQ-6H15AV2
order: ac
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
