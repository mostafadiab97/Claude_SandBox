---
id: REQ-EHFWE9R
type: test-case
title: "Verify: Login screen limits the connection state"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - accessibility
former-id: TC-0C4NSS
parent: REQ-WR5ZJN9
order: aC
links:
  - type: verifies
    target: REQ-PM3KZFS
    confirmed: cf666200a270
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
