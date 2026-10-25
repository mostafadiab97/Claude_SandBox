---
id: TC-VD31W2
type: test-case
title: "Verify: Tamper detection stores audit records"
status: Draft
owner: N. Kamal
tags:
  - EMC
  - release-1.0
  - connectivity
parent: INFO-Z4TW4B
order: 400
links:
  - type: verifies
    target: SYS-SAV1GY
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
