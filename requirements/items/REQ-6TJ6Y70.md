---
id: REQ-6TJ6Y70
type: test-case
title: "Verify: Backlight restores safety limits"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - cost
former-id: TC-1DZD2G
parent: REQ-Y9VHHKA
order: b0w
links:
  - type: verifies
    target: REQ-HJS4CX9
    confirmed: 09253c52493b
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
