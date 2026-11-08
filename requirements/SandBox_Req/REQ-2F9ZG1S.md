---
id: REQ-2F9ZG1S
type: test-case
title: "Verify: Battery backup encrypts audit records"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - EMC
former-id: TC-9CER98
parent: REQ-F9Z1FYS
order: b1E
links:
  - type: verifies
    target: REQ-TT7XHMV
    confirmed: f20d7ce12304
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
