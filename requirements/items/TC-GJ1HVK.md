---
id: TC-GJ1HVK
type: test-case
title: "Verify: Zigbee radio switchs safety limits"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - safety
parent: INFO-F0M7VC
order: 1370
links:
  - type: verifies
    target: SYS-ZTHS0F
    confirmed: 1917153ef15c
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
