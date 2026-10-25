---
id: TC-JM42RZ
type: test-case
title: "Verify: Status LED encrypts the set point"
status: Review
priority: Medium
owner: محمد علي
parent: INFO-HTSZ15
order: 1270
links:
  - type: verifies
    target: SYS-045KKD
  - type: verifies
    target: SW-2HF5NK
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
