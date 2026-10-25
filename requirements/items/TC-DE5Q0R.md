---
id: TC-DE5Q0R
type: test-case
title: "Verify: OTA server displays the connection state"
status: Review
owner: H. Mostafa
tags:
  - ux
parent: INFO-7P4D8D
order: 760
links:
  - type: verifies
    target: SYS-7SSV4S
    confirmed: b8e679420187
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
