---
id: TC-6WRZDR
type: test-case
title: "Verify: Battery backup logs error conditions"
status: Approved
priority: High
owner: R. Nabil
tags:
  - release-1.0
  - release-2.0
  - i18n
parent: INFO-MACGC3
order: 1290
links:
  - type: verifies
    target: SYS-NYK3S8
  - type: verifies
    target: SW-DWKGYH
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
