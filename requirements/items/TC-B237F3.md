---
id: TC-B237F3
type: test-case
title: "Verify: Zigbee radio measures the connection state"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - connectivity
  - performance
parent: INFO-F0M7VC
order: 1310
links:
  - type: verifies
    target: SYS-C5SNMV
    confirmed: aa7b6b73deff
  - type: verifies
    target: SW-KBEPSC
    confirmed: be1f80f82e4f
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
