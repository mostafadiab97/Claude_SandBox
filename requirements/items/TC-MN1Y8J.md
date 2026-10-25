---
id: TC-MN1Y8J
type: test-case
title: "Verify: Device registry validates error conditions"
status: Draft
owner: R. Nabil
tags:
  - release-2.0
parent: INFO-7P4D8D
order: 960
links:
  - type: verifies
    target: SYS-06G288
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
