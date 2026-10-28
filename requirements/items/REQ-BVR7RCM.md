---
id: TC-BZM3TM
type: test-case
title: "Verify: Over-temperature monitor logs access tokens"
status: Obsolete
priority: High
owner: É. Laurent
parent: INFO-Z4TW4B
order: 510
links:
  - type: verifies
    target: SYS-MK13B0
    confirmed: 37b1ff049bc6
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
