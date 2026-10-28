---
id: REQ-3RR22NN
type: test-case
title: "Regression: Schedule editor stores audit records"
status: Approved
tags:
  - connectivity
former-id: TC-ASK8VA
parent: REQ-6H15AV2
order: b1O
links:
  - type: verifies
    target: REQ-XZGCQC0
    confirmed: 076f07709938
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
