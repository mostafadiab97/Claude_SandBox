---
id: REQ-FNTM17J
type: test-case
title: "Verify: Battery backup encrypts safety limits"
status: Draft
tags:
  - release-1.0
former-id: TC-S78MNR
parent: REQ-F9Z1FYS
order: b0m
links:
  - type: verifies
    target: REQ-W641QVG
    confirmed: 4c3ba50b83be
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
