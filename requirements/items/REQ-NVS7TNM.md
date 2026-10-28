---
id: REQ-NVS7TNM
type: test-case
title: "Verify: Power supply stores the room temperature"
status: Review
priority: Low
owner: K. Tanaka
tags:
  - ux
  - accessibility
  - i18n
former-id: TC-X3AYM5
parent: REQ-F9Z1FYS
order: aC
links:
  - type: verifies
    target: REQ-S3STR5Z
    confirmed: 665bbcd834f8
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
