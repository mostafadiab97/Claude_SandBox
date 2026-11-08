---
id: REQ-3299NNW
type: test-case
title: "Regression: Over-temperature monitor logs access tokens"
status: Draft
priority: High
owner: É. Laurent
former-id: TC-3W4C5J
parent: REQ-6H15AV2
order: b1b
links:
  - type: verifies
    target: REQ-7XBRPQY
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
