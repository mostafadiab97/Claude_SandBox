---
id: REQ-DGJP2BY
type: test-case
title: "Verify: Relay board validates sensor readings"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
former-id: TC-QB9XJ5
parent: REQ-F9Z1FYS
order: b1R
links:
  - type: verifies
    target: REQ-02W5PGR
    confirmed: c8a11d5e856a
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
