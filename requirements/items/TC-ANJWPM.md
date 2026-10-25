---
id: TC-ANJWPM
type: test-case
title: "Verify: Bluetooth LE link calibrates access tokens"
status: Review
priority: High
owner: H. Mostafa
tags:
  - EMC
  - connectivity
  - safety
parent: INFO-F0M7VC
order: 1360
links:
  - type: verifies
    target: SYS-WTMBDQ
  - type: verifies
    target: SW-BY3NBC
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
