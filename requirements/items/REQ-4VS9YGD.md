---
id: REQ-4VS9YGD
type: test-case
title: "Verify: Status LED switchs firmware images"
status: Review
priority: Medium
owner: J. Müller
tags:
  - cost
former-id: TC-3K6B01
parent: REQ-Y9VHHKA
order: aW
links:
  - type: verifies
    target: REQ-D27CYAA
    confirmed: e09a5200d69b
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
