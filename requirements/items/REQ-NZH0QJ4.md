---
id: REQ-NZH0QJ4
type: test-case
title: "Verify: User account service calibrates energy consumption"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - customer-request
  - release-2.0
  - i18n
former-id: TC-PX2VM0
parent: REQ-8351896
order: b0A
links:
  - type: verifies
    target: REQ-EEZQ79J
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
