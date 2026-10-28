---
id: TC-JRF9AF
type: test-case
title: "Verify: Cloud backend logs access tokens"
status: Draft
priority: Medium
owner: M. Farouk
parent: INFO-7P4D8D
order: 1000
links:
  - type: verifies
    target: SYS-4FGGM0
    confirmed: 08bb9f68e463
  - type: verifies
    target: SW-02H99V
    confirmed: 72ab5f08e287
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
