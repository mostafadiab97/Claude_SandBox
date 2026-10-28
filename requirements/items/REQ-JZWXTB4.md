---
id: TC-KMSMJY
type: test-case
title: "Verify: Watchdog reports the connection state"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-Z4TW4B
order: 1200
links:
  - type: verifies
    target: SYS-21RSPB
    confirmed: 6d6c12313a2b
  - type: verifies
    target: SW-YDB75D
    confirmed: 63cf0f5701dc
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
