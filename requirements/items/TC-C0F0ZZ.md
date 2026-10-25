---
id: TC-C0F0ZZ
type: test-case
title: "Regression: Boiler interface notifys user preferences"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-ECHASH
order: 1410
links:
  - type: verifies
    target: SYS-AZWQYS
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
