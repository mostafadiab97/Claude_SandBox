---
id: TC-M5QBZ2
type: test-case
title: "Regression: OTA server measures energy consumption"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
parent: INFO-ECHASH
order: 1200
links:
  - type: verifies
    target: SYS-86C690
    confirmed: 69daa9458ae7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
