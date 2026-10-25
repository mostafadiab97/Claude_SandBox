---
id: TC-Z1EQNA
type: test-case
title: "Verify: Bluetooth LE link limits relay events"
status: Approved
priority: High
tags:
  - safety
  - security
  - customer-request
parent: INFO-F0M7VC
order: 870
links:
  - type: verifies
    target: SYS-GD5QC7
    confirmed: ec1a86cc2ebb
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
