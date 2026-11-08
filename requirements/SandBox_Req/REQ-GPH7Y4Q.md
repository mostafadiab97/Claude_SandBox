---
id: REQ-GPH7Y4Q
type: test-case
title: "Verify: OTA server displays schedule entries"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
  - accessibility
former-id: TC-JVT5FC
parent: REQ-8351896
order: ak
links:
  - type: verifies
    target: REQ-0TWE1Z1
    confirmed: 0ce68205e703
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
