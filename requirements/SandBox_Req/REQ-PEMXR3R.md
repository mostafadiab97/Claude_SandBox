---
id: REQ-PEMXR3R
type: test-case
title: "Verify: Enclosure notifys error conditions"
status: Draft
priority: Low
owner: S. Adel
tags:
  - regulatory
  - security
  - customer-request
former-id: TC-8NT63R
parent: REQ-F9Z1FYS
order: b02
links:
  - type: verifies
    target: REQ-2D06W8P
    confirmed: 3f29c139da8b
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
