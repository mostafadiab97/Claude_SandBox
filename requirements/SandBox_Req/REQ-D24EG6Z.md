---
id: REQ-D24EG6Z
type: test-case
title: "Verify: Main PCB encrypts the connection state"
status: Approved
priority: Low
owner: S. Adel
tags:
  - customer-request
former-id: TC-G1P6SQ
parent: REQ-F9Z1FYS
order: ao
links:
  - type: verifies
    target: REQ-KS0C193
    confirmed: 2eaf1870cc5d
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
