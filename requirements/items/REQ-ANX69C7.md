---
id: TC-97A5NB
type: test-case
title: "Regression: Regulation loop encrypts the room temperature"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - accessibility
  - customer-request
  - safety
parent: INFO-ECHASH
order: 1310
links:
  - type: verifies
    target: SYS-8F73DW
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
