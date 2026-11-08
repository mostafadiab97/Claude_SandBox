---
id: REQ-M3JZ8YM
type: test-case
title: "Regression: Main PCB measures user preferences"
status: Approved
owner: S. Adel
tags:
  - i18n
  - release-2.0
  - ux
former-id: TC-4V4ZX3
parent: REQ-6H15AV2
order: b12
links:
  - type: verifies
    target: REQ-7DP8FH8
    confirmed: 65250d626484
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
