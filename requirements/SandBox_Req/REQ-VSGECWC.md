---
id: REQ-VSGECWC
type: test-case
title: "Verify: Battery backup restores schedule entries"
status: Approved
priority: High
tags:
  - accessibility
  - release-2.0
former-id: TC-5RVPR6
parent: REQ-F9Z1FYS
order: ak
links:
  - type: verifies
    target: REQ-2ST0NQA
    confirmed: 220d5e428bbc
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Display firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
