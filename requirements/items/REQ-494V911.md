---
id: TC-RR0GZZ
type: test-case
title: "Verify: Home dashboard switchs schedule entries"
status: Approved
priority: Low
owner: J. Müller
tags:
  - accessibility
  - EMC
  - release-2.0
parent: INFO-J0FETE
order: 570
links:
  - type: verifies
    target: SYS-KE3ZCS
    confirmed: "131852556952"
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
