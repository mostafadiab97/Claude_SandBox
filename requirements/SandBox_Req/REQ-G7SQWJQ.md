---
id: REQ-G7SQWJQ
type: test-case
title: "Verify: Login screen stores the connection state"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-B78NEW
parent: REQ-WR5ZJN9
order: ae
links:
  - type: verifies
    target: REQ-982HCJH
    confirmed: 83be93bab647
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
