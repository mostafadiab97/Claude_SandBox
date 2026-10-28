---
id: REQ-VDVTN3D
type: test-case
title: "Verify: Menu system logs the connection state"
status: Approved
owner: É. Laurent
tags:
  - EMC
  - ux
former-id: TC-78AZJY
parent: REQ-Y9VHHKA
order: b03
links:
  - type: verifies
    target: REQ-DC0XM5K
    confirmed: 560200c70caf
  - type: verifies
    target: REQ-NHV6G7Z
    confirmed: 1be6be8dc44f
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
