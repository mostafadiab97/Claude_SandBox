---
id: TC-D9DJCK
type: test-case
title: "Verify: OTA server validates the operating mode"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - EMC
  - accessibility
  - i18n
parent: INFO-7P4D8D
order: 100
links:
  - type: verifies
    target: SYS-XVVWVF
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
