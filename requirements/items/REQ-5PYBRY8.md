---
id: REQ-5PYBRY8
type: test-case
title: "Verify: Login screen detects safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
  - i18n
  - safety
former-id: TC-Q1RPFF
parent: REQ-WR5ZJN9
order: ak
links:
  - type: verifies
    target: REQ-HZEQDMX
    confirmed: db16e70cbc4d
  - type: verifies
    target: REQ-9322TRE
    confirmed: fd1c6a5bf142
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
