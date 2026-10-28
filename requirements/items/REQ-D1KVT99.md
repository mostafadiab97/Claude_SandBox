---
id: TC-5D4A6Q
type: test-case
title: "Verify: Zigbee radio restores firmware images"
status: Obsolete
owner: محمد علي
parent: INFO-F0M7VC
order: 540
links:
  - type: verifies
    target: SYS-H1Z00Y
    confirmed: 36bbc40bd419
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Validate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
