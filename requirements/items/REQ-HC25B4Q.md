---
id: TC-K31Q9K
type: test-case
title: "Regression: Heat pump driver logs safety limits"
status: Draft
priority: Low
owner: R. Nabil
parent: INFO-ECHASH
order: 720
links:
  - type: verifies
    target: SYS-ZMJ6E1
    confirmed: 4932bfcc9ac4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
