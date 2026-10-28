---
id: REQ-0WNCVF5
type: test-case
title: "Verify: Relay board reports safety limits"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-2.0
former-id: TC-R3ZY0E
parent: REQ-F9Z1FYS
order: b0C
links:
  - type: verifies
    target: REQ-27VHM11
    confirmed: 5f0cd41f8d2d
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
