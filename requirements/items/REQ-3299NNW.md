---
id: TC-3W4C5J
type: test-case
title: "Regression: Over-temperature monitor logs access tokens"
status: Draft
priority: High
owner: É. Laurent
parent: INFO-ECHASH
order: 1620
links:
  - type: verifies
    target: SYS-MK13B0
    confirmed: 37b1ff049bc6
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
