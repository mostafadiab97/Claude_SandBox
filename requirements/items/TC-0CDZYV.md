---
id: TC-0CDZYV
type: test-case
title: "Verify: Zigbee radio measures safety limits"
status: Draft
priority: Low
owner: A. Hassan
parent: INFO-F0M7VC
order: 1470
links:
  - type: verifies
    target: SYS-28RZAE
  - type: verifies
    target: SW-V5P1XD
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
