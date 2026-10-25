---
id: TC-BPGCQM
type: test-case
title: "Verify: Login screen logs the operating mode"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - customer-request
parent: INFO-J0FETE
order: 830
links:
  - type: verifies
    target: SYS-A45TJB
  - type: verifies
    target: SW-VXT0WC
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
