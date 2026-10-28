---
id: REQ-WXR099G
type: test-case
title: "Verify: Backlight switchs audit records"
status: Review
priority: Medium
owner: محمد علي
tags:
  - EMC
former-id: TC-9H820S
parent: REQ-Y9VHHKA
order: at
links:
  - type: verifies
    target: REQ-R8BDX9R
    confirmed: b34c573d4b49
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Switch audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
