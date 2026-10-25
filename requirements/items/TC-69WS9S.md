---
id: TC-69WS9S
type: test-case
title: "Verify: Cloud backend encrypts safety limits"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - accessibility
  - regulatory
  - power
parent: INFO-7P4D8D
order: 560
links:
  - type: verifies
    target: SYS-0HAZNH
    confirmed: 8fef3f917b7b
  - type: verifies
    target: SW-E26XKQ
    confirmed: 744ae3d7d7c5
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
