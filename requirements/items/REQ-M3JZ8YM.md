---
id: TC-4V4ZX3
type: test-case
title: "Regression: Main PCB measures user preferences"
status: Approved
owner: S. Adel
tags:
  - i18n
  - release-2.0
  - ux
parent: INFO-ECHASH
order: 1270
links:
  - type: verifies
    target: SYS-H9YARC
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
