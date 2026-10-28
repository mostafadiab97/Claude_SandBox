---
id: TC-7NEFRV
type: test-case
title: "Verify: User account service measures error conditions"
status: Approved
priority: Medium
tags:
  - release-2.0
parent: INFO-7P4D8D
order: 950
links:
  - type: verifies
    target: SYS-XZE9DK
    confirmed: 7345ac77c8fe
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
