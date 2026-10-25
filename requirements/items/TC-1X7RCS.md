---
id: TC-1X7RCS
type: test-case
title: "Verify: Cloud backend switchs sensor readings"
status: Draft
owner: H. Mostafa
parent: INFO-7P4D8D
order: 1130
links:
  - type: verifies
    target: SYS-X09T8H
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
