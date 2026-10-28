---
id: REQ-VFGNPQX
type: test-case
title: "Verify: OTA server stores audit records"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-1.0
former-id: TC-B5P3GT
parent: REQ-8351896
order: b02
links:
  - type: verifies
    target: REQ-QYR5017
    confirmed: 93e192f9b401
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Validate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
