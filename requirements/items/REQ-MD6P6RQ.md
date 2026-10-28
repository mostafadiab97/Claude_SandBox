---
id: REQ-MD6P6RQ
type: test-case
title: "Verify: Main PCB authenticates relay events"
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - accessibility
  - security
former-id: TC-7CFRGA
parent: REQ-F9Z1FYS
order: b1a
links:
  - type: verifies
    target: REQ-86ACT2C
    confirmed: c34ac0cd30f1
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
