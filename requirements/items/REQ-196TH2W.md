---
id: REQ-196TH2W
type: test-case
title: Hub verification 2
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - safety
  - connectivity
former-id: TC-S911FW
parent: REQ-6H15AV2
order: aA
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 4639507190ed
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
