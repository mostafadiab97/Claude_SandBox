---
id: REQ-SYR73Z0
type: test-case
title: Hub verification 7
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
  - EMC
  - cost
former-id: TC-GQMB0Y
parent: REQ-6H15AV2
order: aF
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Validate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
