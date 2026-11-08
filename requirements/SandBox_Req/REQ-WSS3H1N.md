---
id: REQ-WSS3H1N
type: test-case
title: "Verify: Main PCB switchs humidity values"
status: Approved
owner: محمد علي
tags:
  - power
former-id: TC-A1BB7R
parent: REQ-F9Z1FYS
order: aB
links:
  - type: verifies
    target: REQ-1VNKX7H
    confirmed: a4e7c0d76393
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
