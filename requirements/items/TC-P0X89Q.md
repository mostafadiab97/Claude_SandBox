---
id: TC-P0X89Q
type: test-case
title: "Verify: OTA server restores schedule entries"
status: Draft
priority: Low
owner: M. Farouk
parent: INFO-7P4D8D
order: 420
links:
  - type: verifies
    target: SYS-6YV024
  - type: verifies
    target: SW-VD99JH
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
