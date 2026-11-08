---
id: REQ-0FCAXA9
type: test-case
title: Hub verification 36
status: Approved
owner: N. Kamal
tags:
  - performance
  - customer-request
former-id: TC-Q0F264
parent: REQ-6H15AV2
order: ai
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
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
