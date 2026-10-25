---
id: TC-ZH1R7D
type: test-case
title: "Verify: Bluetooth LE link switchs humidity values"
status: Approved
owner: J. Müller
tags:
  - i18n
  - EMC
  - release-1.0
parent: INFO-F0M7VC
order: 10
links:
  - type: verifies
    target: SYS-EXGREK
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
