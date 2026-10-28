---
id: REQ-6PVAGDD
type: test-case
title: "Verify: Zigbee radio reports the set point"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
  - EMC
former-id: TC-P7028Q
parent: REQ-67RQXCK
order: aX
links:
  - type: verifies
    target: REQ-V4M0FNZ
    confirmed: ba220c3ea923
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
