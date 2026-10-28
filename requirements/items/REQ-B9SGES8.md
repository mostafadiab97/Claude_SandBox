---
id: REQ-B9SGES8
type: test-case
title: "Verify: Device registry switchs the connection state"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - safety
  - security
former-id: TC-5MZNA0
parent: REQ-8351896
order: b1Z
links:
  - type: verifies
    target: REQ-SDZFT6Q
    confirmed: 52a4389d660e
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
