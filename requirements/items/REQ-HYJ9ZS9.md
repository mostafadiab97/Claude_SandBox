---
id: TC-E8TY9H
type: test-case
title: "Regression: Login screen encrypts error conditions"
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-ECHASH
order: 1250
links:
  - type: verifies
    target: SYS-2Y9FGT
    confirmed: 4c561d45744d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
