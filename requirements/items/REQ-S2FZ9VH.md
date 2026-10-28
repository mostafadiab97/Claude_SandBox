---
id: TC-NFTTC1
type: test-case
title: "Verify: Zigbee radio calibrates error conditions"
status: Review
priority: Low
owner: M. Farouk
tags:
  - release-2.0
  - power
parent: INFO-F0M7VC
order: 1220
links:
  - type: verifies
    target: SYS-V3JY7R
    confirmed: a0359a8db234
  - type: verifies
    target: SW-8RHSPC
    confirmed: 35cf08e99025
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
