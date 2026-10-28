---
id: REQ-1K6FTGW
type: test-case
title: "Regression: Backlight limits the connection state"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - release-2.0
  - regulatory
former-id: TC-ZJPJ4Q
parent: REQ-6H15AV2
order: b0M
links:
  - type: verifies
    target: REQ-WP33HKX
    confirmed: c316125af8be
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
