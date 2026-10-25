---
id: TC-RYHE43
type: test-case
title: "Regression: Secure boot measures schedule entries"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - performance
  - EMC
parent: INFO-ECHASH
order: 600
links:
  - type: verifies
    target: SYS-EJR3YH
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
