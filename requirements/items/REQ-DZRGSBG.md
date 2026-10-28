---
id: REQ-DZRGSBG
type: test-case
title: "Verify: Menu system encrypts schedule entries"
status: Approved
priority: High
owner: A. Hassan
tags:
  - release-1.0
  - EMC
  - cost
former-id: TC-1X1EXP
parent: REQ-Y9VHHKA
order: b0x
links:
  - type: verifies
    target: REQ-R42X213
    confirmed: d66b7da9d253
  - type: verifies
    target: REQ-7VX5WH8
    confirmed: 48d10bbe2632
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
