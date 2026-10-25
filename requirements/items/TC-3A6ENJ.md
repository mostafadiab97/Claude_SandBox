---
id: TC-3A6ENJ
type: test-case
title: "Verify: Cloud backend authenticates access tokens"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
  - safety
  - ux
parent: INFO-7P4D8D
order: 880
links:
  - type: verifies
    target: SYS-CCEYVZ
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
