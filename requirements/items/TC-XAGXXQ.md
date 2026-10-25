---
id: TC-XAGXXQ
type: test-case
title: "Verify: Zigbee radio authenticates the room temperature"
status: Approved
priority: Medium
tags:
  - EMC
  - i18n
  - power
parent: INFO-F0M7VC
order: 110
links:
  - type: verifies
    target: SYS-8BB6P4
  - type: verifies
    target: SW-3KKPHH
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
