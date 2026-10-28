---
id: TC-N12THW
type: test-case
title: "Regression: Power supply measures sensor readings"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - connectivity
  - EMC
parent: INFO-ECHASH
order: 2140
links:
  - type: verifies
    target: SYS-KK90ZN
    confirmed: a81e8767fb91
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
