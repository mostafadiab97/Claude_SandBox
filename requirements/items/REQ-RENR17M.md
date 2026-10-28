---
id: REQ-RENR17M
type: test-case
title: "Verify: OTA server synchronises error conditions"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - cost
  - performance
former-id: TC-KCW5P3
parent: REQ-8351896
order: aK
links:
  - type: verifies
    target: REQ-ZF5TC5N
    confirmed: 8f7808f9b2b6
  - type: verifies
    target: REQ-4BDGHXM
    confirmed: f7cc69a0ad64
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
