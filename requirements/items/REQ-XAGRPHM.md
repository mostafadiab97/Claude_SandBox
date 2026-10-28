---
id: TC-CM6FES
type: test-case
title: "Verify: Relay board reports audit records"
status: Obsolete
priority: High
owner: H. Mostafa
tags:
  - regulatory
  - connectivity
  - security
parent: INFO-MACGC3
order: 850
links:
  - type: verifies
    target: SYS-YF7TFF
    confirmed: 7c6e8f945766
  - type: verifies
    target: SW-WMJ9PD
    confirmed: 793dc861b61b
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
