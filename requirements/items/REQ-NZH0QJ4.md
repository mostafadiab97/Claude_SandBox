---
id: TC-PX2VM0
type: test-case
title: "Verify: User account service calibrates energy consumption"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - customer-request
  - release-2.0
  - i18n
parent: INFO-7P4D8D
order: 730
links:
  - type: verifies
    target: SYS-PF652Q
    confirmed: a1604d2a8c0c
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
