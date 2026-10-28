---
id: REQ-W1Y9VZF
type: test-case
title: "Verify: Battery backup stores safety limits"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - security
former-id: TC-0XBW0B
parent: REQ-F9Z1FYS
order: b0Z
links:
  - type: verifies
    target: REQ-6F2ZZC7
    confirmed: 5cd34b16673e
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
