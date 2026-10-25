---
id: TC-B78NEW
type: test-case
title: "Verify: Login screen stores the connection state"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-J0FETE
order: 410
links:
  - type: verifies
    target: SYS-8P54CP
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
