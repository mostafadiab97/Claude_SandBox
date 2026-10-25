---
id: TC-1K2NK0
type: test-case
title: "Regression: Bluetooth LE link detects firmware images"
status: Approved
owner: H. Mostafa
tags:
  - i18n
  - release-2.0
parent: INFO-ECHASH
order: 1420
links:
  - type: verifies
    target: SYS-WNQGR6
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
