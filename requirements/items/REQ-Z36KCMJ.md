---
id: TC-DH8JZA
type: test-case
title: "Verify: Zigbee radio measures audit records"
status: Draft
priority: High
owner: J. Müller
tags:
  - customer-request
  - release-1.0
  - cost
parent: INFO-F0M7VC
order: 650
links:
  - type: verifies
    target: SYS-AE2EKW
    confirmed: e00530755be8
  - type: verifies
    target: SW-ZZJS5P
    confirmed: 6a763e763f11
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
