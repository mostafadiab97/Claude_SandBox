---
id: REQ-29T5TMN
type: test-case
title: Hub verification 33
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - ux
former-id: TC-FRVX8N
parent: REQ-6H15AV2
order: af
links:
  - type: verifies
    target: REQ-KK9EHP7
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
