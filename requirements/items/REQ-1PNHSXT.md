---
id: REQ-1PNHSXT
type: test-case
title: "Regression: Telemetry pipeline validates audit records"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - customer-request
  - i18n
former-id: TC-DDF9RY
parent: REQ-6H15AV2
order: b02
links:
  - type: verifies
    target: REQ-V3SSX4W
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
