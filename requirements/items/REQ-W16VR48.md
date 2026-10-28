---
id: REQ-W16VR48
type: test-case
title: "Verify: Login screen limits sensor readings"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - EMC
former-id: TC-21PVRS
parent: REQ-WR5ZJN9
order: b0R
links:
  - type: verifies
    target: REQ-Y9F757T
    confirmed: 24c104aab763
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
