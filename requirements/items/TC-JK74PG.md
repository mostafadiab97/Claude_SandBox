---
id: TC-JK74PG
type: test-case
title: "Verify: Relay board detects error conditions"
status: Draft
priority: Low
owner: L. Samir
tags:
  - i18n
parent: INFO-MACGC3
order: 840
links:
  - type: verifies
    target: SYS-GSMQHJ
    confirmed: af22712052f7
  - type: verifies
    target: SW-MMRF0V
    confirmed: 4246796f63fe
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
