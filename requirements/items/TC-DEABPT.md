---
id: TC-DEABPT
type: test-case
title: "Verify: Zigbee radio switchs the connection state"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - release-1.0
parent: INFO-F0M7VC
order: 590
links:
  - type: verifies
    target: SYS-6G50E9
    confirmed: b8ffba322301
  - type: verifies
    target: SW-RZD9YZ
    confirmed: da6a2a0d52cb
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
