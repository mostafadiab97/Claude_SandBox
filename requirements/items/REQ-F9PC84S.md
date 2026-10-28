---
id: REQ-F9PC84S
type: test-case
title: "Verify: Wi-Fi module restores access tokens"
status: Draft
priority: High
owner: J. Müller
tags:
  - safety
  - cost
  - customer-request
former-id: TC-50GTK8
parent: REQ-67RQXCK
order: ak
links:
  - type: verifies
    target: REQ-M54QCCE
    confirmed: c7a17f22b84b
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Synchronise safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
