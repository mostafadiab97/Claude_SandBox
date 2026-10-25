---
id: TC-53WT3P
type: test-case
title: "Regression: Heat pump driver notifys humidity values"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - EMC
parent: INFO-ECHASH
order: 2020
links:
  - type: verifies
    target: SYS-K8C5H7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
