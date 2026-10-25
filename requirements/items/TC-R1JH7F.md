---
id: TC-R1JH7F
type: test-case
title: "Verify: Relay board switchs schedule entries"
status: Draft
priority: High
owner: A. Hassan
parent: INFO-MACGC3
order: 920
links:
  - type: verifies
    target: SYS-DK3Y4R
  - type: verifies
    target: SW-HWXS3J
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
