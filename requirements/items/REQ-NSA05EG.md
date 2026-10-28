---
id: TC-JFJVSN
type: test-case
title: "Verify: User account service reports humidity values"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - release-2.0
  - regulatory
  - EMC
parent: INFO-7P4D8D
order: 690
links:
  - type: verifies
    target: SYS-DQWVMQ
    confirmed: 7c9cac507365
  - type: verifies
    target: SW-E9VX7X
    confirmed: 08754fdc2692
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
