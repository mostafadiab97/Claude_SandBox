---
id: TC-VJM4H0
type: test-case
title: "Verify: OTA server displays user preferences"
status: Draft
owner: R. Nabil
parent: INFO-7P4D8D
order: 1090
links:
  - type: verifies
    target: SYS-EK761P
    confirmed: db6748ce1b10
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
