---
id: REQ-4Q3GY25
type: test-case
title: Hub verification 3
status: Review
priority: Medium
owner: J. Müller
tags:
  - power
former-id: TC-X44GFQ
parent: REQ-6H15AV2
order: aB
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
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
