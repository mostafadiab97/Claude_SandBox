---
id: TC-30HZ7Q
type: test-case
title: "Verify: OTA server stores audit records"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - regulatory
  - accessibility
  - EMC
parent: INFO-7P4D8D
order: 450
links:
  - type: verifies
    target: SYS-6QFCF2
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
