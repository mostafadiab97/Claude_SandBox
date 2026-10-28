---
id: TC-Y8D9BB
type: test-case
title: "Verify: Touch display displays the connection state"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - security
parent: INFO-HTSZ15
order: 400
links:
  - type: verifies
    target: SYS-19PSY9
    confirmed: 6a61bda8a792
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
