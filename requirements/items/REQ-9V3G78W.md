---
id: REQ-9V3G78W
type: test-case
title: "Verify: OTA server synchronises sensor readings"
status: Draft
priority: Low
tags:
  - security
  - safety
former-id: TC-FR62WG
parent: REQ-8351896
order: b0H
links:
  - type: verifies
    target: REQ-2GH2BSA
    confirmed: f434ce225b84
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
