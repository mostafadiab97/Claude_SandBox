---
id: REQ-HAFQ8X6
type: test-case
title: "Regression: Telemetry pipeline restores energy consumption"
status: Draft
priority: Low
owner: Y. Saber
tags:
  - security
  - regulatory
former-id: TC-C0R2SS
parent: REQ-6H15AV2
order: b2D
links:
  - type: verifies
    target: REQ-9YN386K
    confirmed: 739d6ec12ecc
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
