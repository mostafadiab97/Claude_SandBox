---
id: REQ-HN7NGGP
type: test-case
title: "Verify: Battery backup synchronises audit records"
status: Approved
priority: High
owner: A. Hassan
tags:
  - cost
  - accessibility
former-id: TC-WYSX28
parent: REQ-F9Z1FYS
order: b19
links:
  - type: verifies
    target: REQ-RZP5BR6
    confirmed: 17b58a826b61
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
