---
id: REQ-1FBFNMC
type: test-case
title: "Verify: Menu system stores sensor readings"
status: Obsolete
priority: High
owner: محمد علي
tags:
  - release-2.0
  - ux
former-id: TC-GXZ7HH
parent: REQ-Y9VHHKA
order: aq
links:
  - type: verifies
    target: REQ-ZDN307J
    confirmed: 8815ccfb397d
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
