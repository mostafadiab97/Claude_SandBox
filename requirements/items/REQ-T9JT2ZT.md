---
id: REQ-T9JT2ZT
type: test-case
title: "Verify: OTA server validates the operating mode"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - EMC
  - accessibility
  - i18n
former-id: TC-D9DJCK
parent: REQ-8351896
order: a9
links:
  - type: verifies
    target: REQ-244HGW6
    confirmed: f37bc3493af5
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
