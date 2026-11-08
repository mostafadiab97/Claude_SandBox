---
id: REQ-A8BMST8
type: test-case
title: "Verify: Relay board detects relay events"
status: Approved
priority: High
owner: Y. Saber
tags:
  - safety
  - cost
  - release-1.0
former-id: TC-A6N327
parent: REQ-F9Z1FYS
order: aL
links:
  - type: verifies
    target: REQ-6W1TW82
    confirmed: fadbb8266e08
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Notify user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
