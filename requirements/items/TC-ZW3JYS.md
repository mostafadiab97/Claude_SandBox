---
id: TC-ZW3JYS
type: test-case
title: "Verify: Cloud backend restores the connection state"
status: Draft
priority: High
owner: É. Laurent
tags:
  - release-2.0
  - connectivity
parent: INFO-7P4D8D
order: 50
links:
  - type: verifies
    target: SYS-3BVVSM
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
