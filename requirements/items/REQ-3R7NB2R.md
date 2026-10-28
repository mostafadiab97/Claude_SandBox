---
id: TC-3TBQPF
type: test-case
title: "Verify: Zigbee radio restores firmware images"
status: Review
priority: High
owner: R. Nabil
tags:
  - cost
parent: INFO-F0M7VC
order: 640
links:
  - type: verifies
    target: SYS-PN9GQ2
    confirmed: fb057a0da125
  - type: verifies
    target: SW-G3D5M2
    confirmed: b739d638789a
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
