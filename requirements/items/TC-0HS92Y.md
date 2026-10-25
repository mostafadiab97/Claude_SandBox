---
id: TC-0HS92Y
type: test-case
title: Hub verification 5
status: Draft
priority: High
owner: N. Kamal
parent: INFO-ECHASH
order: 140
links:
  - type: verifies
    target: SYS-K3Z0CT
---
**Objective:** verify that the thermostat behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the thermostat with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
