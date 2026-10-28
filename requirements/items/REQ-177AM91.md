---
id: TC-93AH8N
type: test-case
title: "Verify: Bluetooth LE link switchs user preferences"
status: Review
priority: Low
owner: N. Kamal
tags:
  - accessibility
  - security
parent: INFO-F0M7VC
order: 750
links:
  - type: verifies
    target: SYS-SB9M68
    confirmed: f26633d7c346
  - type: verifies
    target: SW-4QYJ90
    confirmed: d438cc191c58
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
