---
id: REQ-9M2GEGH
type: test-case
title: "Verify: Main PCB authenticates sensor readings"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - connectivity
former-id: TC-NMYSVT
parent: REQ-F9Z1FYS
order: b1K
links:
  - type: verifies
    target: REQ-JYRD71Q
    confirmed: 86b1e408d2e0
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
