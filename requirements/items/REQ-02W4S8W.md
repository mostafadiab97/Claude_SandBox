---
id: REQ-02W4S8W
type: test-case
title: "Verify: Status LED displays humidity values"
status: Obsolete
priority: High
owner: J. Müller
tags:
  - security
former-id: TC-W7PXYY
parent: REQ-Y9VHHKA
order: b1Q
links:
  - type: verifies
    target: REQ-X70NK7E
    confirmed: f255e71521d5
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
