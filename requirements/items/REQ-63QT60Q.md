---
id: TC-KGK67Q
type: test-case
title: Hub verification 20
status: Draft
priority: High
owner: A. Hassan
tags:
  - customer-request
parent: INFO-ECHASH
order: 290
links:
  - type: verifies
    target: SYS-K3Z0CT
    confirmed: 8c08ebec4abb
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
