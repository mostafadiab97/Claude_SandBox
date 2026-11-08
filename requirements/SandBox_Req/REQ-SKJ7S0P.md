---
id: REQ-SKJ7S0P
type: test-case
title: "Verify: Relay board encrypts user preferences"
status: Obsolete
priority: High
owner: H. Mostafa
tags:
  - power
  - cost
former-id: TC-W6WTQ4
parent: REQ-F9Z1FYS
order: b1G
links:
  - type: verifies
    target: REQ-0VFCCR7
    confirmed: 7b8641948b25
  - type: verifies
    target: REQ-8W2J8VB
    confirmed: f0c87b0c4ded
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Detect user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
