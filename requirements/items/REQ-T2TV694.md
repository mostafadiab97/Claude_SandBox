---
id: TC-YDNEYD
type: test-case
title: "Verify: Zigbee radio authenticates relay events"
status: Approved
priority: High
owner: S. Adel
parent: INFO-F0M7VC
order: 880
links:
  - type: verifies
    target: SYS-VGDQPF
    confirmed: 3d1d8edc4849
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
