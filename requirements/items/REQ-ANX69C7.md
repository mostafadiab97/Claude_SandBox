---
id: REQ-ANX69C7
type: test-case
title: "Regression: Regulation loop encrypts the room temperature"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - accessibility
  - customer-request
  - safety
former-id: TC-97A5NB
parent: REQ-6H15AV2
order: b16
links:
  - type: verifies
    target: REQ-QG4NKYK
    confirmed: 13efe84ae7ac
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
