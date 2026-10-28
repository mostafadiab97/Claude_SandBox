---
id: TC-588E6V
type: test-case
title: "Verify: Cloud backend stores safety limits"
status: Approved
owner: محمد علي
parent: INFO-7P4D8D
order: 1530
links:
  - type: verifies
    target: SYS-7EMY0G
    confirmed: c4f3af124d96
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
