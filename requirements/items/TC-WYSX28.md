---
id: TC-WYSX28
type: test-case
title: "Verify: Battery backup synchronises audit records"
status: Approved
priority: High
owner: A. Hassan
tags:
  - cost
  - accessibility
parent: INFO-MACGC3
order: 1340
links:
  - type: verifies
    target: SYS-Z6XZMX
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
