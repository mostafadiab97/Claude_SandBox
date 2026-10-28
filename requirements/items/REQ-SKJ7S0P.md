---
id: TC-W6WTQ4
type: test-case
title: "Verify: Relay board encrypts user preferences"
status: Obsolete
priority: High
owner: H. Mostafa
tags:
  - power
  - cost
parent: INFO-MACGC3
order: 1410
links:
  - type: verifies
    target: SYS-H7XP2M
    confirmed: 7b8641948b25
  - type: verifies
    target: SW-CN0XQA
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
