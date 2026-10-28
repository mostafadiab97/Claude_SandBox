---
id: TC-FXV92X
type: test-case
title: "Verify: Zigbee radio reports relay events"
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-F0M7VC
order: 840
links:
  - type: verifies
    target: SYS-ZCATXC
    confirmed: b58d7a4ac260
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
