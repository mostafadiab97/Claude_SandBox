---
id: REQ-X88KV7P
type: test-case
title: "Regression: Telemetry pipeline logs sensor readings"
status: Review
priority: Low
tags:
  - release-2.0
  - i18n
former-id: TC-5J3X28
parent: REQ-6H15AV2
order: b0I
links:
  - type: verifies
    target: REQ-X8M7P49
    confirmed: 7d8bc76969c6
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
