---
id: TC-6P5P8K
type: test-case
title: "Regression: Encryption layer calibrates the connection state"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - security
parent: INFO-ECHASH
order: 1760
links:
  - type: verifies
    target: SYS-1HN03J
    confirmed: e85c5bf1399b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
