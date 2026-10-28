---
id: TC-S9WHY3
type: test-case
title: "Regression: Schedule editor measures relay events"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - connectivity
  - security
parent: INFO-ECHASH
order: 2060
links:
  - type: verifies
    target: SYS-XGRV2A
    confirmed: 99dfb3c74c30
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
