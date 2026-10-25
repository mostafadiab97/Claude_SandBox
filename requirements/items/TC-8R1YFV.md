---
id: TC-8R1YFV
type: test-case
title: "Regression: Encryption layer notifys humidity values"
status: Draft
priority: Medium
owner: Y. Saber
parent: INFO-ECHASH
order: 1320
links:
  - type: verifies
    target: SYS-1F01HM
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
