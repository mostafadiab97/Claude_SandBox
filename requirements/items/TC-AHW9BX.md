---
id: TC-AHW9BX
type: test-case
title: "Verify: Zigbee radio displays error conditions"
status: Approved
priority: High
owner: Y. Saber
tags:
  - i18n
  - connectivity
  - EMC
parent: INFO-F0M7VC
order: 40
links:
  - type: verifies
    target: SYS-5CGTBY
  - type: verifies
    target: SW-0ZHFRT
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
