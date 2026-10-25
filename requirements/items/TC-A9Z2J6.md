---
id: TC-A9Z2J6
type: test-case
title: "Verify: Cloud backend logs audit records"
status: Approved
priority: High
owner: M. Farouk
tags:
  - accessibility
  - release-2.0
parent: INFO-7P4D8D
order: 1330
links:
  - type: verifies
    target: SYS-5KZ5DB
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
