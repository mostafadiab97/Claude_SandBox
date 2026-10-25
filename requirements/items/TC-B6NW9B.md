---
id: TC-B6NW9B
type: test-case
title: "Verify: Local API switchs access tokens"
status: Approved
priority: High
owner: L. Samir
tags:
  - connectivity
  - safety
  - customer-request
parent: INFO-F0M7VC
order: 1010
links:
  - type: verifies
    target: SYS-32XAX6
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Notify relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
