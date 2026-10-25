---
id: TC-AF9W82
type: test-case
title: "Verify: Enclosure authenticates firmware images"
status: Obsolete
priority: High
owner: محمد علي
tags:
  - accessibility
  - performance
  - release-1.0
parent: INFO-MACGC3
order: 990
links:
  - type: verifies
    target: SYS-ES2T78
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
