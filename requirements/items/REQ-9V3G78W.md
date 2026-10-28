---
id: TC-FR62WG
type: test-case
title: "Verify: OTA server synchronises sensor readings"
status: Draft
priority: Low
tags:
  - security
  - safety
parent: INFO-7P4D8D
order: 800
links:
  - type: verifies
    target: SYS-DH9YV1
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
