---
id: TC-G1GDYN
type: test-case
title: "Verify: Cloud backend switchs sensor readings"
status: Approved
priority: High
owner: محمد علي
tags:
  - cost
  - power
  - performance
parent: INFO-7P4D8D
order: 850
links:
  - type: verifies
    target: SYS-ANP21Y
    confirmed: 3e91619f12fb
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
