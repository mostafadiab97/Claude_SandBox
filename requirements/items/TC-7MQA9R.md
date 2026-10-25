---
id: TC-7MQA9R
type: test-case
title: "Verify: Encryption layer calibrates firmware images"
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-Z4TW4B
order: 1430
links:
  - type: verifies
    target: SYS-MG3QAE
  - type: verifies
    target: SW-TEJ96F
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
