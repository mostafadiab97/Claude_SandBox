---
id: TC-9DBPTK
type: test-case
title: "Verify: Pairing process validates sensor readings"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - performance
  - i18n
  - release-2.0
parent: INFO-F0M7VC
order: 20
links:
  - type: verifies
    target: SYS-B9VTJR
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
