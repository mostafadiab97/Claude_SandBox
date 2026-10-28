---
id: TC-DDF9RY
type: test-case
title: "Regression: Telemetry pipeline validates audit records"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - customer-request
  - i18n
parent: INFO-ECHASH
order: 650
links:
  - type: verifies
    target: SYS-MK2A6C
    confirmed: f66b9f28edb5
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
