---
id: TC-JVT5FC
type: test-case
title: "Verify: OTA server displays schedule entries"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
  - accessibility
parent: INFO-7P4D8D
order: 470
links:
  - type: verifies
    target: SYS-GBXCHX
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
