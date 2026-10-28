---
id: TC-3TV2DX
type: test-case
title: "Regression: Pairing process limits energy consumption"
status: Approved
owner: J. Müller
tags:
  - performance
  - customer-request
  - regulatory
parent: INFO-ECHASH
order: 1340
links:
  - type: verifies
    target: SYS-KJZDA6
    confirmed: cceccc292cf6
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
