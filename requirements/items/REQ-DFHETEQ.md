---
id: TC-YZHG2R
type: test-case
title: "Verify: Zigbee radio switchs relay events"
status: Draft
priority: High
owner: É. Laurent
tags:
  - release-2.0
  - i18n
  - power
parent: INFO-F0M7VC
order: 390
links:
  - type: verifies
    target: SYS-DHYCNS
    confirmed: 9adddfa5a009
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
