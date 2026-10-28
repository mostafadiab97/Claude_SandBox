---
id: REQ-CH77XZB
type: test-case
title: "Verify: OTA server synchronises sensor readings"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
  - safety
former-id: TC-MVY50N
parent: REQ-8351896
order: b0a
links:
  - type: verifies
    target: REQ-TP2GDPC
    confirmed: fce90764ac1a
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
