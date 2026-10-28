---
id: REQ-YGS3RG9
type: test-case
title: "Verify: OTA server stores audit records"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - regulatory
  - accessibility
  - EMC
former-id: TC-30HZ7Q
parent: REQ-8351896
order: ai
links:
  - type: verifies
    target: REQ-3P9VR9B
    confirmed: d9f6d0d7d66b
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
