---
id: TC-W1BXKG
type: test-case
title: "Regression: Bluetooth LE link detects access tokens"
status: Approved
owner: K. Tanaka
tags:
  - security
  - regulatory
  - performance
parent: INFO-ECHASH
order: 940
links:
  - type: verifies
    target: SYS-2N03B4
    confirmed: 9597e83a664b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
